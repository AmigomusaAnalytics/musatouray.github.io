---
layout: post
title:  "Real-Time Live TV Presidential Elections Report"
author: sal
categories: [ Jekyll, tutorial ]
image: assets/images/gambia-presidential-elections.jpg
---
This project is special to me as it is about national service. I was contracted by the National TV Station of The Gambia (my country) to help broadcast on the national TV, live results of 2021 presidential election.

Because it was to be aired on live TV, I needed to set up the dashboard refresh every 30 seconds or less. Also, I had the limitation of not having Premium Capacity license to content with. To mitigate these constraints, I created a Powerapp to capture the election results data as they're made available by the election commission using Azure SQL Server as data source. In Power BI, I use Direct Query mode to connect to the Azure SQL instance for live results data. Finally, I use the Play Axis Custom Visual to set the refresh at every 30 seconds which amazingly refreshes the report in the Power BI Service every time there is live data without any restriction and displays it on the TV.
