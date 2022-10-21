---
title: "Voice Scenario"
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

## Voice Scenario

![Title](/images/gsol_story_conversion.png)

<div class="row">
  <div class="col">
<br><b><u>Talk Track</u></b><br><br><br>
    {customer} has now had the Solar Panels installed and is starting to enjoy the benefits of the energy savings, but last night an ice storm moved through his/her town and damaged several of the solar panels.
    <br>{customer} has been using his/her smart phone for all communication since the storm. He/She needs to call GSol to start an claim.
  </div>
  <div class="col">
  <br><b><u>Click Track</u></b><br><br><br>
    <b>Call GSol phone number</b>
    <br><br><br>A Voice Bot answers and asks "Thank you for contacting GSOL, How can I help you?"
  </div>

  <div class="col">
  </div>
</div>

<div class="row">
  <div class="col">
    I want to file a claim
  </div>
  <div class="col">
  What product has been affected?
  </div>
  <div class="col"></div>
</div>

<div class="row">
  <div class="col">
    Panasonic solar panels
  </div>
  <div class="col">
    How many items have to be replaced?  
 </div>
  <div class="col"></div>
</div>

<div class="row">
  <div class="col">
    5
  </div>
  <div class="col">
    We are sorry that some of our products have been damaged. Your claim is being processed one moment please. Your claim for five Panasonic solar panels has been processed. claim number is GSC 0792 the replacement will be shipped tomorrow. We will send you a confirmation.
    <br><br> Is there anything else I can I do for you?
 </div>
  <div class="col"></div>
</div>

<div class="row">
  <div class="col">
    Speak to an agent
    <br>Predictive Routing will leverage Genesys AI to connect {customer} with the best possible Agent.
  </div>
  <div class="col">
    In PurecloudNow
    <br>Accept incoming Call
 </div>
  <div class="col"></div>
</div>

<div class="row">
  <div class="col">
    What is your return policy?
  </div>
  <div class="col">
    Select the Agent Assist panel
    <br>Show how the voice Agent Assist suggests an answer for the asked question.

 </div>
  <div class="col"></div>
</div>

<div class="row">
  <div class="col">
    {customer} is happy. His/Her new panels are on the way and GSol made it easy.
  </div>
  <div class="col">
   End call. Assign Wrap Up Code
 </div>
  <div class="col"></div>
</div>