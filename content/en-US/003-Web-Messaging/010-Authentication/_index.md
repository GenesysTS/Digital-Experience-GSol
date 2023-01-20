---
title: "Authentication"
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

![Title](/images/WebM.PNG)

## Authentication

### Passing data to the Architect Flow

GSol uses [Database plugin](https://developer.genesys.cloud/commdigital/digital/webmessaging/messengersdk/SDKCommandsEvents) of Messenger JavaScript SDK to pass user data and login related information to the Architect's Inbound Message Flow.

As a result the access to some operations is closed for the users who are not logged in into GSol web site.

<div class="row">
  <div class="col">
<br><b><u>User logged out</u></b><br>

![One](/images/gsol-dgt-balance-logout.png)

  </div>
  <div class="col">
  <br><b><u>User logged in</u></b><br>

![One](/images/gsol-dgt-balance-login.png)
  </div>

  <div class="col">
  
  </div>
</div>
