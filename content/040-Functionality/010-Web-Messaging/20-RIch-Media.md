---
title: "Rich Media"
chapter: true
weight: 10
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

{{% notice note %}}
> Notes: The activation of the Web Messaging will be remebered and stay active till the moment when browser's data are cleared.
{{% /notice %}}

## Authenticated Bot Flow

### Passing data to the Architect

GSol uses [Database plugin](https://developer.genesys.cloud/commdigital/digital/webmessaging/messengersdk/SDKCommandsEvents) of Messenger JavaScript SDK to pass user data and login related information to the Architect's Inbound Message Flow.

As a result the access to some operations is closed for the users who are not logged in into GSol web site.

## Rich Media

<div class="row">
  <div class="col">

[Quick Replies - Intent Switching](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)

![Quick replies](/images/dx_gsol_bot_intent.png)

</div>

<div class="col">

[Quick Replies - Slot filling](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)

![Slot](/images/dx_gsol_bot_slots.png)

</div>
</div>

<div class="row">
  <div class="col">

[Cards - Intent switching ](https://help.mypurecloud.com/articles/work-with-cards-in-bot-conversations/)  

![Card Intent](/images/dx_gsol_bot_card.png)

</div>

<div class="col">

[Quick Replies - Dynamic Slot](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)

![Dynamic Slot](/images/dx_gsol_bot_slot_dynamic.png)

</div>
</div>
