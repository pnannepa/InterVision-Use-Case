Inbound Flow:

Checks contact attributes block to determine if the contact is contacting by phone or chat, and to route accordingly.

If Contact Channel is either chat or task, the contact is transferred to the Queue configurations.

If Contact Channel is voice, then based on user input the contact is transferred to the other flows.

Queue Configurations:

1. The customer is put in the ClaimHelp queue.

2. Then queue flow is invoked. This block runs a Loop prompts block that plays the following:

    "Thank you for calling. Your call will be answered in the order it was received."

3.  Hours of operation are checked with a Check hours of operation block.

4.  The channel is checked for chat, voice or

    For chat, the time in queue is checked. If it's less than 5 minutes, the customer is placed in queue for an agent. If it's more, channel again is checked again 
    and if it's chat, put the customer in queue for an agent.

    For voice, the customer is routed down the No Match branch, and then to a Get customer input block.
