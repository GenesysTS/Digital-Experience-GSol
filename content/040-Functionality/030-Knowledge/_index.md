---
title: "Knowledge Management"
chapter: true
weight: 70
---

<style>
td, th {
   border: none!important;
}
.row {
    display: flex;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .col {
        flex: 0 0 100%;
        max-width: 100%;
        padding: 25px;
    }
}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .col {
        flex: 0 0 100%;
        max-width: 100%;
        padding: 25px;
    }
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .col {
        flex: 0 0 100%;
        max-width: 100%;
        padding: 25px;
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .col {
        flex: 0 0 50%;
        max-width: 50%;
        padding: 10px 25px;
    }
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .col {
        flex: 0 0 50%;
        max-width: 50%;
        padding: 10px 25px;
    }
}

</style>
# Knowledge management

Genesys Cloud offers a powerful way to manage knowledge across multiple touchpoints. Whether information is needed  across the online presence via the bots, the Support Center and Smart Advisor.

- Support Center
- Bot Knowledge
- Smart Advisor


## Support Center

There are 2 ways to expose the Support Center on GSol website.
#### Method 1

1. Hover your mouse cursor over **Messenger** icon   (1)  
2. Click on the appearing icon with a question mark  (2)  .

#### Method 2

1. Press **"Magnifying glass"** icon
2. The text specified in the web site's search field will be tranferred into **Support Center's** search field.

![One](/images/gsol-dgt-support-center-search.png)

Once Support Center is opened, browse articles or search for the knowledge.

## Bot knowledge

<div class="row">
  <div class="col">

If the bot intent has not match, the bot performs a search in the GSol Knowledge base and expose the information to the online visitor.

<br>

Any unanswered questions will be available in Knowledge Optimizer to improve the self-service containment rate.

</div>
<div class="col">
  
![bot-knowledge](/images/dx_gsol_knowledge_bot.png)

</div>
</div>

## Smart Advisor

Smart Advisor suggests an answer based on customer's question to help agents be more efficient and to stay current on the latest information available.

### Pre-requisites

In order to showcase Smart Advisor, you need to update your GDemo customer record. 
This information is used in the Architect flow when the chat is transferred to a customer representative to define the appropriate queue.

![smart-advisor-1](/images/dx_gsol_smart_advisor_1.png)

{{% notice warning %}}
> Don't forget to add your PCN Agent to the GSol Customer Service queue if you want to use Smart Advisor capabilities
{{% /notice %}}


![smart-advisor-1](/images/gsol_smart_adv_2.png)

At this time, Smart Advisor is only available to the Digital Desktop

### Scenario

- Open Digital Desktop
- Launch Web Messenger from GSol website
- Ask the benefits of Solar Panels from GSol chat
- Request Customer Representative
- While chatting with an agent, ask "How long does a solar panel last?" 

You will be able to see suggestions of relevant articles in real-time to the agent.

![smart-advisor-1](/images/gsol-smart-advisor-3.png)
## Available articles

- Am I eligible for solar tax credit?
- What is a Tax Credits
- How many solar panels do I need?
- Do solar panels need a lot of maintenance?
- What are the benefits of solar panels?
- How long do solar panels last?
- How long do refunds take?
- What is your refund policy?
- What payment types do you accept?
