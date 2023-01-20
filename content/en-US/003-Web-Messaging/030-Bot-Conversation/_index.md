---
title: "Bot Conversations"
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

![Title](/images/WebM.PNG)

## Bot conversation

See below the bot conversations currently available in our GSol demo:

- Appointment
- Balance
- Customer Churn
- Meter Readinfg
- Order Delivery Status
- Refund
- Power Outage
- Product Advisor
- Escalation to Agent

### Dialog Engine Bot


<div class="row">
  <div class="col">
    <br><br><br><br><br><b><u>Appointment</u></b><br>
    Select "Appointment" quick reply or enter
    <br>- "I need to book an appointment"
    <br>- "I need to book an appointment"
    <br>- "I would like to book an appointment"


  </div>
  <div class="col">
  <img height="300px" src="/images/gsol-msg-appt.gif">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  </div>
</div>

<div class="row">
  <div class="col">
    <br><br><br><br><br><b><u>Product Advisor</u></b><br>
    Select "Product Advisor" quick reply or enter
  </div>
  <div class="col">
  <img height="300px" src="/images/gsol-msg-pa.gif">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  </div>
</div>

| Intent      | Sample phrases | Answer / Action|
|-------------|-----------------|-------------------|
| balance | - I want to know my balance<br>- What is my balance<br>- Can you send me my balnce by SMS please | Your outstanding balance is ... |
| Meter Reading | - My meter reading is 13465<br>- I want to provide a meter reading<br>- meter reading | The bot helps to collect a meter reading. |
| churn | - I want to close my account because I want to<br>switch provider<br>- I want to close my account because of the move<br>- I want to close my account<br>- I would like to cancel my subscription<br>- I want to disconnect my service | The bot asks the customer for the account closure reason and connect him to an agent.|
| Order Status | - Is my order coming soon? <br> - Where is my stuff?<br>- Where is my order 12345<br>- Where is my order?<br> |  The bot asks for the order number and provides a status update:<br>"Your order 12345 is due for delivery tomorrow."|
| Representative | - Talk to an agent? <br> - Talk to the representative<br>- I would like to speak to an advisor<br>- Connect me to an advisor please<br> |  The bot transfers to an agent |
| Exit | - Goodbye <br> - Exit |  Conversation is finished |
| No Match |  If no intent found the bot performs a search in the GSol knowledge base | [Additional info here]({{< relref "/005-Knowledge/" >}} "Knowledge")  |
