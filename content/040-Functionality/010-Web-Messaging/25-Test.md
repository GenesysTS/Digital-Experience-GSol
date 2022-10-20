---
title: "Rich Media Test"
chapter: true
weight: 20
---

Genesys Cloud web messaging provides customers with an enhanced experience when they visit your website. Unlike web chat, which provides short-lived, standalone chats, web messaging enables a visitor to enter your site, converse with a bot or agent, and return later to pick up the conversation. With Predictive Engagement, agents can view the entire customer journey as part of the web messaging interaction. Web messaging shares many of the same features and capabilities as the other Genesys Cloud messaging channels that use ACD messaging to enable agents to respond to customer interactions.

*   [Authentication / Passing data to the Architect - Inbound Message Flow](/demos/633c7799126303f47028a577#msg_authentication)
*   [Predictive Engagement](/demos/633c7799126303f47028a577#msg_gpe)
*   [Rich media](/demos/633c7799126303f47028a577#msg_richmedia)
*   [Bot conversation](/demos/633c7799126303f47028a577#msg_bots)

#### Authentication / Passing data to the Architect - Inbound Message Flow

GSol uses [Database plugin](https://developer.genesys.cloud/api/digital/webmessaging/messengersdk/SDKCommandsEvents) of Messenger JavaScript SDK to pass user data and login related information to the Architect's Inbound Message Flow.  
As a result the access to some operations is closed for the users who are not logged in into GSol web site.

 User logged out

 User logged in

  ![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-balance-logout.png)

  ![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-balance-login.png)

#### Predictive Engagement

"Predictive Engagement scenarios" section describes scenarious implemented on **GSol** web site.   
All of them are supported with Web Messaging.

Web Chat and Web Messaging Proactive Engagement chat offers look differently.

Below is the example Web Messaging Proactive Engagement chat offer for "Reduce Abandoment Rate" scenario.  
See "Predictive Engagement scenarios" for the scenario's details.

![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-gpe-invite.png)

Notes:

*   "Reset Altocloud" at the bottom of the web site prior to every demonstration.

#### Rich media

 [Cards - Intent switching](https://help.mypurecloud.com/articles/work-with-cards-in-bot-conversations/)

 [Quick Replies - Intent switching](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)

 [Quick Replies - Slot filling](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)

 ![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-cards.png)

 ![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-qr-intents.png)

 ![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-qr-slots-static.png)

[Quick Replies - Slot filling](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/) (Dynamic)

 

 

![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-qr-slots-dynamic.png)

 

 

#### Bot conversation

In general, bot conversation in Web Messaging match bot conversation in Web Chat. 

Web Messaging specific is listed below. 

 

 Intent 

 Sample phrases

 Answer / Action

 appointment

   
 Select "**Appointment**" quick reply  
  
      or enter   

*   I need to book an appointment
*   I would like to book an appointment

 - Confirmation message  
 - Confirmation SMS  
 - Proactive notification

 Dates and Times are generated for every appointment.

 balance

*   I want to know my balance
*   What is my balance
*   Can you send me my balnce by SMS please

 Your outstanding balance is ...  
  
 

 churn

*   I want to close my account because I want to _switch provider_
*   I want to close my account because of the _move_ 
*   I want to close my account
*   I would like to cancel my subscription
*   I want to disconnect my service

 The bot asks the customer for the account closure reason and connect him to an agent.

 meterReading

*   My meter reading is _13465_
*   I want to provide a meter reading
*   meter reading

 The bot helps to collect a meter reading.

 orderStatus

*   Where is my order _12345_
*   Is my order coming soon?
*   Where is my staff?
*   Where is my order?

 The bot asks for the order number and provides a status update:  
"Your order 12345 is due for delivery tomorrow."

 **powerOutage**

*   there is no electricity at my place
*   I want to report a power outage
*   no power at my house
*   power outage
*   I have a power outage at my house

![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-cards.png)

 **refund**

*   I got my shipment but there's a problem
*   I didn't receive the package I ordered online
*   There is a defect in my package
*   I didn't receive the package I ordered online
*   I need a refund
*   How can I get a refund of my solar panels?
*   I ordered a Canadian  Solar Panel and I received a different one
*   Can you schedule a pickup for the incorrect product tomorrow at noon?
*   You shipped me the wrong solar panel

 

 

 

 

 representative 

 Talk to an agent  |  Talk to the representative  |  Connect me to an advisor please  
 I would like to speak to an advisor / talk to the representative

 Transfer to an agent

 exit

 Goodbye / Exit

 Conversation is finished

 <no-match?

  If no intent found the bot performs a search in the knowledge base

 

**intent**  \- intent handled by Google Dialogflow using the approach below:

![](https://gdemo.demo.genesys.com/api/gdemo-assets/demos/GSol/gsol-dgt-de-2-gdf.png)

The reason for using several bots could be:

1.  Migration from Google Dialogflow to Genesys Dialog Engine 
2.  Bots orchestration (diffrent bots do better different things)

Having Dialog Engine in front makes sure that all customer's queries are captured and used in the **Optimizer** and **Intent Miner**