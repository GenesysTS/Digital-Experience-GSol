---
title: "Voice"
chapter: true
weight: 120
---

![Title](/images/voice.PNG)

You can reach GSol Customer Service with this number: **(+1) 866-288-8546**
 

## Personalization

Depending on your customer profile, you will be offered a personalized service on the phone. To illustrate this personalization, we created 3 segments 'High Value Shopper', 'Customer Care Needed', and 'Customer' and we are using Genesys Predictive Engagement to update the customer segment based on the customer web activities in this demo.

### Self-Service Bot

If you do not visit the website, a voice bot will be offered to you. The voice bot offers similar capabilities as the chatbots.
<br>For additional reference, please refer to the "Web Messaging: Bot conversations" section.
You can also reset the customer segment using the link in the footer 'Reset Customer Segment' to demo the voice bot.

![One](/images/file_1637598294651_GPE_reset_segments.png)

### Sales Support Scenario. 
A known visitor arrives at the GSol GDemo website. The visitor places item(s) in a shopping cart: 

- Genesys Predictive Engagement identifies the visitor as a Segment “High-Value Shopper” based upon the shopping cart dollar amount value or based upon the specific items placed into the cart. Select the Renogy Solar Panel item (+$500)
- The Visitor calls the Business “GSol”.  When a Segment is matched prior to a call, the Segment may be correlated with a “Call Intent”.
- An inbound call Architect Flow recognizes the visitor and the matched “High-Value Shopper Segment” and plays an audible IVR prompt “Hello xxx. Are you calling about the items in your shopping cart today? Say ‘yes’ or press 1 to be routed to a Sales Specialist. 
- Route the call the appropriate Queue/Skill/Agent
- As the Agent answers the call, the GPE Customer Journey, Identity Stitching journey visualization may be selected and displayed.  The Agent may now see the Outcome Scores and any Segments matched along with current and historical interaction and journey information to address the customer’s call Intent “Complete a Purchase”
 

### VIP Care Scenario. 
A known visitor arrives at the GSol GDemo website. The visitor navigates to Learning and selects “return a product”: 

- Genesys Predictive Engagement identifies the visitor as a Segment “Customer Care Needed” based upon the website behavior navigating to “return a product”. Go to 'Learning' section of the website. Click the 'Maintenance' tile. Expand the first Basics menu 'What is the return policy with Solar Panels'
- The Visitor calls the Business “GSol”.  When a Segment is matched prior to a call, the Segment may be correlated with a “Call Intent”.
- An inbound call Architect Flow recognizes the visitor and the matched “Customer Care Needed” and plays an audible IVR prompt “Hello xxx. Thank you for being a VIP. Are you calling for customer service today? Say ‘yes’ or press 2 to be routed to a Customer Care Specialist. 
- Route the call the appropriate Queue/Skill/Agent
- As the Agent answers the call, the GPE Customer Journey, Identity Stitching journey visualization may be selected and displayed.  The Agent may now see the Outcome Scores and any Segments matched along with current and historical interaction and journey information to address the customer’s call Intent “Customer Care”


![Two](/images/file_1637598327026_GPE_service_segment.png)

## Google Agent Assist

### Scenario

- Launch CX Desktop with PCN
- Call this number: **(+1) 866-288-8546** from your phone
- Ask to speak to an agent
- While talking to an agent, ask him what is the return policy?
- Move to the Agent Assist tab of the CX Desktop
- Show the Return Policy suggestion push to the agent

![Two](/images/agent-assist.png)