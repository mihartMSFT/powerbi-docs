---
title: Connect to Office365Mon with Power BI
description: Office365Mon for Power BI
author: paulinbar
ms.reviewer: maggiesMSFT

ms.service: powerbi
ms.subservice: powerbi-template-apps
ms.topic: conceptual
ms.date: 11/26/2019
ms.author: painbar

LocalizationGroup: Connect to services
---
# Connect to Office365Mon with Power BI
Analyzing your Office 365 outages and health performance data is easy with Power BI and the Office365Mon template app. Power BI retrieves your data, including outages and health probes, then builds an out-of-box dashboard and reports based on that data.

Connect to the [Office365Mon template app](https://msit.powerbi.com/groups/me/getapps/services/office365mon.office365mon_powerbi_v3) for Power BI.

>[!NOTE]
>An Office365Mon admin account is required to connect and load the Power BI template app.

## How to connect
1. Select **Get Data** at the bottom of the nav pane.
   
   ![](media/service-connect-to-office365mon/pbi_getdata.png)
2. In the **Services** box, select **Get**.
   
   ![](media/service-connect-to-office365mon/pbi_getservices.png) 
3. Select **Office365Mon** \> **Get**.
   
   ![](media/service-connect-to-office365mon/o365mon.png)
4. For Authentication Method, select **oAuth2** \> **Sign In**.
   
   When prompted, enter your Office365Mon admin credentials and follow the authentication process.
   
   ![](media/service-connect-to-office365mon/creds.png)
   
   ![](media/service-connect-to-office365mon/creds2.png)
5. After Power BI imports the data you will see a new dashboard, report, and dataset in the nav pane. New items are marked with a yellow asterisk \*, select the Office365Mon entry.
   
   ![](media/service-connect-to-office365mon/dashboard4.png)

**What now?**

* Try [asking a question in the Q&A box](../consumer/end-user-q-and-a.md) at the top of the dashboard
* [Change the tiles](../create-reports/service-dashboard-edit-tile.md) in the dashboard.
* [Select a tile](../consumer/end-user-tiles.md) to open the underlying report.
* While your dataset will be scheduled to refresh daily, you can change the refresh schedule or try refreshing it on demand using **Refresh Now**

## Troubleshooting
If you get a **"login failed"** error after using your Office365Mon subscription credentials to login, then the account you are using doesn't have permissions to retrieve the Office365Mon data from your account. Verify it is an admin account and try again.

## Next steps
[What is Power BI?](../fundamentals/power-bi-overview.md)

[Get Data for Power BI](service-get-data.md)
