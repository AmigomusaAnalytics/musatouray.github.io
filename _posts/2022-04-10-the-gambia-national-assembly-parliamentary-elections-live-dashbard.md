---
layout: post
title:  "The Gambia National Assembly / Parliamentary Elections Live Dashboard"
author: Musa Touray
categories: [ Power BI, Data Visualization, Real-Time Analytics]
image: assets/images/gambia-parliamentary-elections.jpg
---
This is a continuation of the above presidential election live dashboard. This project also uses directquery mode to connect to an Azure SQL database. Because it is live TV reporting, I created a Powerapp which feeds incoming election results to the database and that in turn populates the dashboard via refresh set at every 30 seconds.

<p>
    <iframe style="width:100%;" height="383" 
        src="https://app.powerbi.com/view?r=eyJrIjoiYmU3YzkyOTEtNzE4NC00OWI2LWI0NmEtMWZmYjA0ZTcyZjE0IiwidCI6ImU3ZmRiMmEyLTUzODAtNDBmMC04MmQ4LWEzYjU0YzFmODE3ZiJ9&pageName=ReportSection3ff2ccc0849ea42b0023" 
        frameborder="0" allowFullScreen="true">
    </iframe>
</p>