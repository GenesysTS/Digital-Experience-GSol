---
title: "SFDC Integration"
chapter: true
weight: 90
---

![Title](/images/sfdc.PNG)

### Setup
1. Log in into Salesforce
- Obtain the credentials to the PC4SF account under login section of Genesys Cloud for Salesforce demo script
2. Open the Predictive Engagement application (see setup section above).
3. Open the GSol website, and log into it

### Visualize GPE Journey information in SFDC
1. Login to SFDC 
2. Create a new Contact or Edit your existing Salesforce Contact from if not already. Make sure to enter your Predictive Engagement ID as the external contact ID from PCN
3. Go to GSol application, in the contacts tab, select your contact and you should be able to visualize your Customer Journey

![One](/images/file_1604350219466_gsol-1.png)

### Lead Creation
1. Customer navigates to the Utilities section select an item and add it to the cart. Change the quantity to ensure the cart value is higher than $2,000.
2. Customer navigates to Checkout page
3. Customer abandons the checkout form by clicking on the GSol logo.
4. Action map triggers an Architect flow to add the lead to the GSol Campaign in Salesforce
5. The Lead is added to a GSol campaign with the details and description of what might be of interest for the prospect

![Two](/images/sfdc-lead-pc.png)

When you are finished with this scenario, we recommend deleting your lead from Salesforce. If not deleted, only the description and details information will be updated.
