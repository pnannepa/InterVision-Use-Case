Version 1.0

Inbound Flow: A2Z Cloud Services, customer calls via phone or chat and chooses either Sales, Customer Service or Technical Support.  
Depending on the choice made the call or chat is routed.

1.  If the agent is available, it is routed to the agent otherwise queued based on the choice made by the customer.  The customer has a choice to wait or can request a call back.
    Hours of operation are checked with a Check hours of operation block, 
2.  The chat service is either basic chat or Asynchronous Chat.   In Async chat, the customer can disconnect and resume the chat within 4 hours
3.  Call recording and playback are enabled.
4.  Queue and Hold flows is implemented.
5.  Whisper flow is implemented to enable the contact center manager to monitor live conversations between the agent and the customer
6.  Transfer flow and quick connects are enabled.
7.  Realtime metrics and reporting are implemented
8.  Historical metrics and reporting are implemented

Version 2.0

1.  Recording and live monitoring of chat conversations are implemented
2.  Automatic task creation is implemented
3.  AWS Lamba integration with Amazon Connect is implemented

Version 3.0
1.  AWS Lex AI Chatbot is implemented
