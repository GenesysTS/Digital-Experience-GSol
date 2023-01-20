---
title: "Smart Advisor"
chapter: true
weight: 30
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
## Smart Advisor

Smart Advisor suggests an answer based on customer's question to help agents be more efficient and to stay current on the latest information available.

### Pre-requisites

In order to showcase Smart Advisor, you need to update your GDemo customer record. 
This information is used in the Architect flow when the chat is transferred to a customer representative to define the appropriate queue.

![smart-advisor-1](/images/dx_gsol_smart_advisor_1.png)

{{% notice warning %}}
> Don't forget to add your PCN Agent to the **GSOL - Customer Service** queue if you want to use Smart Advisor capabilities. Genesys Partners should add their PCN agents into **GSOL - Partner Customer Service**
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
