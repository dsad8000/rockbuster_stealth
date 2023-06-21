# Rockbuster Stealth
## Analysis of video rental data for business strategy recommendations
## **Objective**

#### Rockbuster Stealth LLC business intelligence department requires a launch strategy for moving their video rental business to a streaming service. The management board has asked for a presentation addressing a number of business questions to inform their 2020 company strategy.
- Which movies contributed the most/least to revenue gain?
- What was the average rental duration for all videos?
- Which countries are Rockbuster customers based in?
- Where are customers with a high lifetime value based?
- Do sales figures vary between geographic regions?

Data was filtered, summarized, and cleaned in PostgreSQL. SQL queries included joining tables and using subqueries, and a data dictionary to explain the relational database was created. Tableau was then used to visualize the data.
 
## **Data Limitations**

#### Data is included for film rentals in 2006, so timeliness is an issue. Data collection after initial implementation of strategic business plan, particularly among the high lifetime value customers as outlined below, will provide guidelines for pivoting in targeted marketing campaigns. Data integrity was checked using SQL queries to identify non-uniform, duplicate, and missing values.
 
## **Analysis and Results**
### [Sample SQL Queries used](https://github.com/dsad8000/rockbuster_stealth/tree/main/sql_queries)

## **Recommendations**

[Tableau dashboard](https://public.tableau.com/app/profile/danielle.sadler6048/viz/RockbusterCustomersandRevenuebyLocation_16802791977730/Top10Countries?publish=yes)

1. Strategically choose markets to roll out the streaming service. Targeting these 10 countries for initial sales and marketing campaigns captures high individual and total revenue potential.
 
<kbd>![Recommendations_1](https://github.com/dsad8000/rockbuster_stealth/assets/98616377/902ef4f2-8e2c-4e16-9fac-6ff2f771698e)<kbd>
 
2. Marketing and sales campaigns target geographic location content preferences based on popular film categories.
 
<kbd>![Recommendations_2](https://github.com/dsad8000/rockbuster_stealth/assets/98616377/510c0b1c-19ce-48a3-973a-a6b5a6797260)<kbd>
 
3. Introduce initial service plan incentives for high lifetime value customers. Customers in the top quarter of revenue are 19% or more of customers in our top 10 revenue countries. A loyalty plan to reward these customers with incentives for the initial service plan will provide data to analyze rental trends for targeted local marketing campaigns.
 
<kbd>![Recommendations_3](https://github.com/dsad8000/rockbuster_stealth/assets/98616377/1bb9f51f-4007-49de-aa58-0652d62cbc0d)<kbd>

 
## **Summary**

<kbd>![Summary](https://github.com/dsad8000/rockbuster_stealth/assets/98616377/bb5581d4-ff4f-4eb6-b25f-9fdfbc97f7b2)<kbd>




