# Restaurant-Business-Intelligence

A collection of Power BI dashboards developed during my time as a Junior Data Analyst for restaurants. These dashboards were built to deliver business-critical insights in areas such as customer behaviour, sales trends and dish performance.

The data for each restaurant was extracted and stored into a series of spreadsheets which were cleaned prior to being loaded into Power BI to power their respective restaurant's dashboards. Then Power BI's data model was optimised in each case through creating relationships across tables (each table being data from a single spreadsheet) for one-to-many joins such as `Category to Items`. Also, Data Analysis Expressions (DAX) were used to create custom dynamic metrics such as Total Orders and Customers, Average Order Value and the numbers of New and Returning Customers. DAX was further utilised to create tables for customer segmentation. 

> **Note**: Due to the sensitive nature of the data, this repository contains only screenshots of the dashboards. The raw Excel spreadsheets and Power BI (`.pbix`) files have not been uploaded to protect customer privacy (e.g. names, emails, phone numbers) and confidential business data.

<details>
  <summary><h2>The Curry Bengal</h2></summary>
  
  ## Customer Insights

  This dashboard provides an end-to-end analysis of customer engagement at The Curry Bengal, based on data from 16/06/2023 to 14/09/2024. It explores trends in customer acquisition, segmentation, consent types, order behaviour, and total spending.

  <img src = "TCB_Customer_Insights.png">

  ### Visuals and Metrics

  - **New vs Returning Customers (Donut Chart)**: Highlights retention performance; a larger returning customer base suggests effective loyalty or satisfaction.
  - **Consent Type Breakdown (Bar Chart)**: Key for assessing the reach of marketing efforts and compliance with consent-based communication.
  - **Customers Grouped by Total Spending (Pie Chart)**: Segments customers into four spending brackets (High, Medium, Low, Reservations) to support targeted promotions.
  - **Number of Orders per Person vs Total Spent (Scatter Plot)**: Aids in identifying high-value customers and frequent visitors for potential loyalty programme prioritisation.
  - **Total Orders Per Day (Line Chart)**: Provides an operational view of restaurant activity and growth trends, helping to optimise staffing and kitchen workflow. Additionally, provides a forecast with a 95% confidence level in order trends.
  - **Top KPI Cards**:
      - Total Customers: 1,989
      - Total Orders: 4,472
      - Cumulative Revenue: £142,695.12
      - Average Order Value: £31.91
      - Average Time of Order: 17:55
   
  ### Insights and Conclusions
  
  - Strong base of returning customers (37%) suggests repeat satisfaction.
  - Majority of customers (over 85%) have opted in to marketing, providing scope for effective campaigning stratagies.
  - Peak activity seen in August–September, possibly influenced by promotions or seasonal trends such as school holidays.
  - Most revenue came from low and medium spenders suggests a potential to personalise offers for those groups.

<br/>

  ## Restaurant Sales and Dishes

  This dashboard analyses sales performance down to individual dishes and categories, highlighting which items drive revenue and where discounts are most impactful. It supports data-driven menu curation and promotional strategies.

  <img src = "TCB_Restaurant_Sales_and_Dishes.png">

  ### Visuals and Metrics

  - **Category Dropdown Menu**: Enable stakeholders to explore performance by category.
  - **Best Selling Items (Bar Chart)**: Ranks dishes clearly by quantity sold - _Papadoms_ lead with 1,003 sales.
  - **Percentage of Total Sales by Category (Donut Chart)**: Reveals the most commercially important categories (e.g. _Vegetable Side Dishes_, _Rice and Sundries_, _Korma Dishes_).
  - **Total Sales Before vs After Discounts by Category (Clustered Column Chart)**: Helps identify which categories are discount-reliant and may be driving lower margins.
  - **Percentage of Total Sales by Item (Pie Chart)**: Offers a complete view of how individual items contribute to revenue - _Chicken Tikka Masala_ dominates at 8.68%.
  - **Highlight Cards**:
    - Total Sales Before Discounts: £18,149.05
    - Total Sales After Discounts: £17,592.72
    - Total Discount Value: £556.33
    - Average Discount per Item: £3.92

  ### Insights and Conclusions
  - _Papadoms_ are high-volume, low-discount items which elucidates that their price can be safely increased or they can be bundled with other orders.
  - Categories like _Vegetable Sides_ and _Rice_ account for large sales volumes confirming their central role in meal structures.
  - Discounts are used relatively moderately, so there is potential to test promotions in underperforming categories.
  - Dish-level insights guide stock management, price revisions, and promotional planning.

</details>

<details>
  <summary><h2>Raj Tandoori</h2></summary>
  
  ## Customer Insights

  This dashboard 

  <img src = "RT_Customer_Insights.png">

  ### Visuals and Metrics

  - 
   
  ### Insights and Conclusions

  -
  
  <br/>
  
  ## Restaurant Sales and Dishes

  This dashboard 

  <img src = "RT_Restaurant_Sales_and_Dishes.png">

  ### Visuals and Metrics

  - 

  ### Insights and Conclusions
  
  - 
 
</details>
