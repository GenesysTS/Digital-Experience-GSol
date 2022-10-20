---
title: "Google Dialogflow"
chapter: true
weight: 40
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

![Title](/images/WebM.PNG)


### Google Dialogflow Bot

Genesys Web Messenger has the capabilities to integrate with several bots provider. In this section, we are exposing the orchestration of the flow with DialogFlow bot to check power outage.



{{% notice note %}}
> The reason for using several bots within Architect flows could be:
> <br>- Migration from Google Dialogflow to Genesys Dialog Engine 
<br>- Bots orchestration (diffrent bots do better different things)
<br> - Having Dialog Engine in front makes sure that all customer's queries are captured and used in the Optimizer and Intent Miner
{{% /notice %}}
