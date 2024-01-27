<h1> Generating Insights in FMCG solve Supply Chain Issue </h1>

<h2>Problem Statement</h2>

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

<h2>Task</h2>

As a Data analyst on this project, my task is to build this dashboard to track the performance of the customers wr.t. to the above discussed KPI's. All the relevant information documents and data are attached in this repository folder. 

<h2>Data Model</h2>

![data model_powerbi](https://github.com/rajmehta26/FMCG-Supply-Chain-Analysis/assets/152624212/63f6f3ba-5e5b-4268-a9f4-8a9ed09cb9da)


<h2>Dashboard</h2>

![overview_powerbi](https://github.com/rajmehta26/FMCG-Supply-Chain-Analysis/assets/152624212/565e021e-a21f-4ff8-b57d-23be2f1726ec)

![Citywise analysis_powerbi](https://github.com/rajmehta26/FMCG-Supply-Chain-Analysis/assets/152624212/57e8c68b-8be1-45f3-8a78-f482bf05ea42)


<h2>Business Insights</h2>

<h3> KPI Insights </h3>

- At 71% On-Time rate, it is well below taregt rate of 86%
- The In-Full rate achieved is 66% against the target of 77%
- The overall On Time In Full rate at 48% is also below the set target of 66%
- The current Line Fill Rate (LIFR) and Volume Fill Rate (VOFR) stands at 66% and 96.6% respectively

 <h3> City & Customer Insights </h3>

<table>
  <tr>
    <th> Parameter </th>
    <th> Ahmedabad </th>
    <th> Surat </th>
    <th> Vadodara </th> 
    <th> Overall </th>
  </tr>
  <tr>
    <th> Top Customer </th>
    <th> Rel Fresh (8.6%) </th>
    <th> Lotus Mart (9.5%) </th>
    <th> Expert Mart (8.7%) </th> 
    <th> Vijay Stores (8.8%) </th> 
  </tr>
  <tr>
    <th> Top Product </th>
    <th> AM Milk 100 (9.7%) </th>
    <th> AM Milk 250 (9.6%) </th>
    <th> AM Milk 250 (9.6%) </th> 
    <th> AM Milk 250 (9.5%) </th> 
  </tr>
  <tr>
    <th> Top Category </th>
    <th> Dairy (78%)  </th>
    <th> Dairy (78%) </th>
    <th> Dairy (78%) </th> 
    <th> Dairy (78%) </th> 
  </tr>
  <tr>
    <th> OT % / Target </th>
    <th> 70% | 86% </th>
    <th> 74% | 86% </th>
    <th> 70% | 86%  </th> 
    <th> 70% | 86%  </th> 
  </tr>
  <tr>
    <th> IF % / Target </th>
    <th> 68% | 77% </th>
    <th> 67% | 77%  </th>
    <th> 64% | 75% </th> 
    <th> 64% | 75% </th> 
  </tr>
  <tr>
    <th> OTIF % / Target </th>
    <th> 48% | 67% </th>
    <th> 51% | 66% </th>
    <th> 45% | 65% </th> 
    <th> 45% | 65% </th> 
  </tr>
  <tr>
    <th> Most ordered weekday </th>
    <th> Tuesday (0.96M) </th>
    <th> Sunday (0.61M) </th>
    <th> Tuesday (0.68M) </th>
    <th> Tuesday (1.96M) </th> 
  </tr>
</table>

  <h3> Product Insights </h3>

  - Dairy is the top selling cateogry with ~78% of the total orders
  - AM Milk 250 is the most ordered product contributing to ~9.5% (1.28M units) of the total orders
  - AM Ghee 100 is the lest sold product with 0.186M units
  - AM Biscuits 750 has the highest LIFR (68.05%) and VOFR (96.85%) rate
  - AM Milk 100 is the most undelivered product with 44,211 units undelivered
  - August has the highest In-Full rate at 66.3% while June has the lowest rate at 65.7%
  - July has the highest On-Time rate at 71.8% while May has the lowest rate at 70.5%
  - The OTIF% rate has remained contant between 47.6% to 48.6% in the 6 months across which the data is measured.
