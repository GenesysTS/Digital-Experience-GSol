---
title: "Tax Credit Offer"
chapter: true
weight: 10
---

## Tax Credit Offer

Genesys Predictive Engagement can display content offers on your website to nudge online visitors at the right moment in time and expose them proper Call To Action.
In our specific scenario, we display a content offer to online visitors when abandoning the form to get quotes for installing a Solar system.

### What is a Genesys Content Offer?

GSol Tax Credit offer is being defined in the Predictive Engagement Action Library as a Genesys content offer described below. Website Administrators can define the content and the style of the content offer to fit your website design principles.

![Zero](/images/gpe-gsol-content-offer-1.png)

In our GSol Tax Credit scenario, this content offer is being displayed to online visitors when matching the 'Abandon Residential Quotes' segment. Administrators can modify the engagement rules from the Genesys Cloud and expose the content offer immediately, after a specific delay or at the next visit to the visitor.

![Zero](/images/gpe-gsol-content-offer-action-map.png)

### GSol Tax Credit Offer scenario

{{% notice info %}}
> Login on the website with your GDemo credentials ahead of the demo to identify the right Genesys Cloud agent for routing purpose.{{% /notice %}}

1. Visit [GSol website](https://gsolgc.demo.genesys.com/)
2. Go to **"Residential"** page and scroll down
3. Fill up all **"Contact Information"** section of the form (similar to GDemo Customer Record)
4. Select **Yes** to the question **"Are you homeowner?"**
5. Click  **Next**

![Zero](/images/dx_gsol_residential_form_1.png)

1. Fill up all **"House Information"** section of the form
2. Enter a zip code and select a value for your monhtly energy bill
3. Click   **Next**  

![Zero](/images/dx_gsol_residential_form_2.png)

1. Abandon **"Savings Estimate"** section of the form
2. **DO NOT** click   **Interested**   button
3. Abandon the form and Click on the GSol icon and redirect to the homepage of GSol 

![Zero](/images/dx_gsol_residential_form_3.png)

Wait for few seconds and the Tax Credit offer will be displayed as a modal

![One](/images/dx_gsol_gpe_tax_credit_offer.png)

- Click on the   **Check it out!**   Call To Action (CTA) button 
- You will be redirected to the **"Tax Credit Advisor"** page with the additional information
