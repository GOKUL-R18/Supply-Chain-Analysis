# AtliQ Mart Supply Chain Analysis
As part of the code basics resume challenge, I have performed data analysis and designed a dashboard in Power BI

Challenge [Link](https://codebasics.io/challenges/codebasics-resume-project-challenge/5)

Live Dashboard [Link](https://app.powerbi.com/view?r=eyJrIjoiZmExMWZlYzItYjZmYi00MzkxLTk4OTYtNzE3ZjkzY2M1ODg5IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&embedImagePlaceholder=true&pageName=ReportSectionbb73b81a4bcbda5959b7)

## Problem statement

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities: Surat, Ahmedabad, and Vadodara. They want to expand to other metro/tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers have not extended their annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily, so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders daily against the target service level set for each customer.


### Task List

Peter Pandey is the data analyst in the supply chain team who joined Atliq Mart recently. He has been briefed about the task in the stakeholder business review meeting. Now, imagine yourself as Peter Pandey and play the role of the new data analyst who is excited to build this dashboard and perform the following tasks

Create the metrics according to the metrics list.
Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in the form of a comic.
Create relevant insights that are not provided in the metric list/stakeholder meeting.


## Data Model 

<p align="center">
  <img src="https://github.com/GOKUL-R18/Supply-Chain-Analysis/blob/main/Resources/data_model.png" height="400">
</p>

## Dashboard 

<p align="center">
  <img src="https://github.com/GOKUL-R18/Supply-Chain-Analysis/blob/main/Resources/Dashboard.jpg" width="300">
</p>

## Some Major Insights 

- All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
- On average, orders are delayed 0.42 days from the agreed date of delivery
- Lotus Mart, Coolblue, and Acclaimed stores have the highest orders as well as the most delays in delivering the products on time 
  - Is it because we are not estimating the right delivery date?
  - Is it because we are receiving more orders than expected?
- Ghee, curd, and butter products are most delayed in delivery. 
- There are no noticeable improvements in any of the key metrics in the last few months
- There is a huge gap in IF% for most of the customers. Is it because of less production?
