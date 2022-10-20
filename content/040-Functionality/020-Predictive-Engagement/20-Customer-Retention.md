---
title: "Customer Retention"
chapter: true
weight: 30
---

## Customer Retention

### Scenario

1. Login into [PureCloudNow](https://login.mypurecloud.com/#/authenticate-adv/org/purecloudnow) organization of Genesys DX
2. Navigate to **Admin > Predictive Engagement > Live Now**
3. Login into Agent Workspace and make your agent **Available**
4. Visit [GSol](https://gsolgc.demo.genesys.com/) website
5. Make sure to click **"Reset Altocloud"** link at the bottom of the page to trigger a proactive chat
6. Login into GSol web site
7. Customer is looking for more information on deleting their account.
8. Customer navigates to the **Learning** page and click on the [Accounts](https://gsoldx.demo.genesys.com/#maintenance) tile.

![One](/images/dx_gsol_gpe_churn_account.png)

9. On the opened **"Maintenance & Support"** page the Customer scrolls down and clicks on **"How do I delete my account"** section.

![One](/images/dx_gsol_gpe_churn_account_1.png)

10. Go to **Contact Us** page
11. Customer Journey in "Live Now" indicates that **"Risk Churn"** segment is assigned to the Customer.

### Configuration

The customer is now at risk of churning and GSol team is trying to understand what are the reason behind this decision. For this reason, the business has set up a specific rules in Predictive Engagement  Predictive Engagement offers a chat.

![One](/images/dx_gso_gpe_churn_action_1.png)


### Agent escalation

Based on Predictive Engagement rules, an offer is presented the online customer to assist him in real-time.

![One](/images/dx_gso_gpe_retention_invite.png)

Customer accepts the chat and a bot offers to talk to an agent.

![Two](/images/dx_gsol_gpe_retention_agent.png)

When distributing an interaction to your GDemo agent, you can showcase 2 different desktops depending on your customer needs:

- CX Desktop
- Digital Desktop

#### CX Desktop (option 1)

[CX Desktop Access](https://login.mypurecloud.com/#/authenticate-adv/org/purecloudnow)

1. The customer answers  **Yes**  and get connected to a retention specialist who can see the journey in his Agent Workspace.
2. The is connected to a retention specialist who can see the journey in his Agent Workspace.

![Three](/images/dx_gsol_gpe_churn_cx_desktop.png)

#### Digital Desktop (option 2)

[Digital Desktop Access](https://apps.mypurecloud.com/digital-desktop/#/work)

1. The customer answers  **Yes**  and get connected to a retention specialist who can see the journey in his Agent Workspace.
2. The is connected to a retention specialist who can see the journey in his Agent Workspace.
3. Smart Advisor provides agents with the answers on a customer's questions in a real-time.

![Three](/images/dx_gsol_gpe_retention_desktop.png)
