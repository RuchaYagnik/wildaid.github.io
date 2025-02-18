---
layout: post
title: "Set up Charts"
date: 2020-06-12 01:00:00 -0400
categories: charts
site: build
---

Before we make any charts, we have to set up the data source to use for Charts.
<BR><BR>
1. In the <A HREF="https://cloud.mongodb.com">web UI at cloud.mongodb.com</A>, select "Charts" at the top:
<img src="/assets/images/GoToCharts.png" style="border:1px solid black" width="100%"><BR><BR><BR><BR>
1. If you see this screen, select the green button to activate Charts.
<img src="/assets/images/ActivateCharts.png" style="border:1px solid black" width="100%"><BR><BR>
1. Select "Data Sources" to add your Atlas database as a source for Charts data:
<img src="/assets/images/ClickDataSources.png" style="border:1px solid black" width="100%"><BR><BR>
1. Select the green "Add Data Source" button.<BR><BR>
1. Choose the Atlas cluster to connect to and select "Next":
<img src="/assets/images/ChooseCluster.png" style="border:1px solid black" width="100%"><BR><BR>
1. Select the checkbox next to your database to select all the collections in the database and then select "Finish":
<img src="/assets/images/ChooseDb.png" style="border:1px solid black" width="100%"><BR><BR>
1. It has worked when you see data sources added to this screen:
<img src="/assets/images/VerifyDataSource.png" style="border:1px solid black" width="100%"><BR><BR>
1. For the BoardingReports data source, select the ellipses and then "External Sharing Options":
<img src="/assets/images/ExtSharing.png" style="border:1px solid black" width="100%"><BR><BR>
1. Set the toggle to "On" to enable external sharing, make sure "Authenticated Embedding Only" is selected, and select the green "Save" button:
<img src="/assets/images/SharingOn.png" style="border:1px solid black" width="100%"><BR><BR>
1. Before we make any charts, we need to create a dashboard to hold the charts. Select "Dashboards":
<img src="/assets/images/ClickDashboards.png" style="border:1px solid black" width="100%"><BR><BR>
1. Select the green "Add Dashboard" button<BR><BR>
1. Add in a title and description and select "Create":
<img src="/assets/images/DashTitleDesc.png" style="border:1px solid black" width="100%"><BR><BR>
1. You should now see an empty dashboard, like this:
<img src="/assets/images/BlankDash.png" style="border:1px solid black" width="100%"><BR><BR>

In the next guide we will be making the simplest chart: the list of boardings.
