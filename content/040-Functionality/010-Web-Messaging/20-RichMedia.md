---
title: "Rich Media"
chapter: true
weight: 20
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

.col {
    flex: 0 0 50%;
    max-width: 50%;
}

.ml-2 {
    padding-top: 20px;
    padding-left: 30px;
}

</style>

## Rich Media

<div class="row">
  <div class="col">
    <img height="600px" class="center-block" src="/images/dx_gsol_bot_card.png">

  </div>
  <div class="col ml-2">
  <br><b><u>Appointment</u></b><br>
    Select "Appointment" quick reply or enter<br>- "I need to book an appointment"<br>- "I need to book an appointment"<br>- "I would like to book an appointment"
    <img height="600px" class="center-block" src="/images/dx_gsol_bot_card.png">
  </div>
</div>



| [Cards - Intent switching ](https://help.mypurecloud.com/articles/work-with-cards-in-bot-conversations/)        | [Quick Replies - Intent Switching](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)  | [Quick Replies - Slot filling](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)        | [Quick Replies - Dynamic Slot](https://help.mypurecloud.com/articles/work-with-quick-replies-in-bot-conversations/)|
| ------------ | ------------- | ------------------ | ------------------ |
|   ![One](/images/dx_gsol_bot_card.png)     |  ![Two](/images/dx_gsol_bot_intent.png)    | ![Three](/images/dx_gsol_bot_slots.png)          |  ![Four](/images/dx_gsol_bot_slot_dynamic.png)     |

## Bot conversation

{{< mermaid >}}
flowchart LR
    id1("Sample Phrases") --> id2{"Intent"} --> id3["Answer / Action"]
{{< /mermaid >}}

<div class="row">
  <div class="col">
    <br><b><u>Appointment</u></b><br>
    Select "Appointment" quick reply or enter<br>- "I need to book an appointment"<br>- "I need to book an appointment"<br>- "I would like to book an appointment"
      



  </div>
  <div class="col">
  <img height="600px" class="center-block" src="/images/gcare_msg_logged_out.gif">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  </div>
</div>


<div class="row">
  <div class="col">
    <img height="600px" class="center-block" src="/images/gcare_msg_logged_out.gif">

  </div>
  <div class="col ml-2">
  <br><b><u>Appointment</u></b><br>
    Select "Appointment" quick reply or enter<br>- "I need to book an appointment"<br>- "I need to book an appointment"<br>- "I would like to book an appointment"
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  </div>
</div>


### Schedule an appointment





| Intent      	| Sample phrases                                                                                                                                                                                                                         	| Answer / Action                                                                                                                     	|
|-------------	|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|-------------------------------------------------------------------------------------------------------------------------------------	|
| **Appointment** 	| Select "Appointment" quick reply or enter<br>- "I need to book an appointment"<br>- "I need to book an appointment"<br>- "I would like to book an appointment"                                                                         	| ![Title](/images/gcare_msg_logged_out.gif)	|
| balance     	| - I want to know my balance<br>- What is my balance<br>- Can you send me my balnce by SMS please                                                                                                                                       	| Your outstanding balance is ...                                                                                                     	|
| churn       	| - I want to close my account because I want to<br>switch provider<br>- I want to close my account because of the move<br>- I want to close my account<br>- I would like to cancel my subscription<br>- I want to disconnect my service 	| The bot asks the customer for the account closure reason and connect him to an agent.                                               	|
|             	|                                                                                                                                                                                                                                        	|                                                                                                                                     	|