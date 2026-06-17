# Adventure Works: Sales & Profitability Audit

## Project Overview
This Power BI dashboard provides a comprehensive audit of sales performance for the fictional company **Adventure Works**. The analysis covers data from **January 2020** to **June 2022**, transforming raw data from the Kaggle repository into actionable insights.

The report is structured into three dedicated pages, each specifically designed to address a core business category: **Net Executive Performance, Pdroduct Quality Audit, and Customer Value**. This ensures a focused approach to operational efficiency and data-driven decision-making.
 

<img width="1347" height="758" alt="image" src="https://github.com/user-attachments/assets/c5b1195b-dc93-41f9-b52d-560da236d4c2" />
<br>
<br>
The first page of the report provides a high-level financial overview, highlighting net revenue calculations, monthly sales growth trends, and the distribution of revenue across different product categories.
<br>
<br>
*Note: The monthly trend chart displays a sharp decline after June because the 2022 dataset concludes mid-year. When the "All" filter is selected, the first six months are artificially inflated by aggregating three years of data (2020–2022), while the remaining months only combine two (2020–2021). Applying a specific year filter corrects this statistical distortion and reveals the true, logical trend.*
<br>
<br>
<img width="1347" height="758" alt="image" src="https://github.com/user-attachments/assets/bde10b56-7ad4-4a8c-8fcc-a1231bfdf417" />
<br>
<br>
The second page of the report focuses on product returns, analyzing peak return periods, comparing return rate growth year-over-year, and quantifying the exact financial impact of these returns on overall revenue.
<br>
<br>
<img width="1347" height="758" alt="image" src="https://github.com/user-attachments/assets/c59fb69e-c99e-4bfc-b3a4-fa092bd14ec1" />
<br>
<img width="300" height="338" alt="image" src="https://github.com/user-attachments/assets/6c48dab8-09b4-4ab7-bd88-f8644ecb29f2" />
<br>
<br>
The third page of the report focuses on customer value analysis, segmenting the customer base across geographic markets and tracking spending trends based on gender and occupation. 
<br>
This section features an interactive, dynamic report-page tooltip (shown in the second image) that automatically filters and displays granular demographic insights—such as education level and income group—when hovering over a specific country or occupation group.
<br>
<br>


# Executive Insights: Addressing Key Business Questions

## 1. Financial Health & Profitability

**Question:** What is our true Net Profit after accounting for returns and inventory recovery?

<img width="480" height="260" alt="image" src="https://github.com/user-attachments/assets/f18204e7-da19-4c6c-b7c8-d106b98dfcf1" />

<br>
<img width="647" height="252" alt="image" src="https://github.com/user-attachments/assets/42809ba3-984c-41fc-81b6-471d103e2155" />
<br>

*   **Exceptional Stability:** The company’s performance is exceptionally stable. The net profit margin has consistently remained above 40% throughout all analyzed years, demonstrating excellent cost control even during periods of rapid revenue growth.

*   **Margin Protection:** Net Profit was stabilized by identifying and removing high-return/low-volume products that were causing operational losses.
  
*   **Expansion Impact:** Adding new product categories significantly grew the customer base and increased total profit.

## 2. Quality Control

**Question:** Which categories drive return rates and how does this affect growth?

<img width="480" height="260" alt="image" src="https://github.com/user-attachments/assets/02630759-b341-4f0c-b735-fef1749f6003" />

<br>
<img width="641" height="313" alt="image" src="https://github.com/user-attachments/assets/d37a9aab-857b-40db-9b81-5ef3f21de63d" />
<br>

*   **High-Stakes Category Risk (Bikes):** Because the Bikes category generates 13 times more profit than Accessories and Clothing combined, its return volume has the most critical impact on overall growth. Fortunately, year-over-year data shows that the bike return rate is steadily decreasing.
*   **Secondary Areas for Examination:** Within the clothing and accessories segments, items like Shorts and Vests show disproportionately high return rates and require a deeper quality or sizing audit.
*   **Risk Diversification Recommendation:** To mitigate the heavy reliance on bike performance, expanding stable "one-product" subcategories - such as Hydration Packs and Bike Racks - is highly recommended to diversify the revenue risk.
*   **Actionable Insight:** Some items, like "Mountain-500" bike, require further review due to its high return rate.
   

## 3. Customer Retention & Regional Performance

**Question:** How effective is our customer conversion and Revenue per Member?

<img width="480" height="260" alt="image" src="https://github.com/user-attachments/assets/1727964d-fb55-46c2-8ced-4f75e46bedc2" />
<br>

<img width="648" height="242" alt="image" src="https://github.com/user-attachments/assets/9424e747-028c-4953-8b07-c52f9cdb42db" />

<br>

*   **The Retention Gap:** While acquisition is high, new growth is outpacing loyalty. This has caused the average Revenue per Member to drop as the database grows without repeat purchases.

*   **Product Assortment Expansion:** Broadening the product catalog (introducing lower-priced items like accessories and clothing alongside high-ticket bikes) successfully tripled the customer base within a single month. While this shift toward lower-priced goods naturally drove down the *Revenue per Member*, the massive surge in transaction volume resulted in a substantial increase in overall profit.

*   **Canada (High Volume, Low AOV):** While transaction frequency is high, customers mostly purchase lower-priced accessories. The strategic focus should be on cross-selling to convert this high-volume pool into first-time bike buyers.
*   **USA (Market Leader & Retention Risk):** Despite being the largest market by volume, the USA suffers from lower revenue per customer and elevated churn. Implementing an upselling campaign for premium bikes is recommended to boost regional ROI.

*   **Australia (High-Efficiency Model):** Australia represents the most efficient market, generating substantial revenue with only half the customer base of the USA. This high-loyalty, high-spend framework serves as the ideal operational benchmark for other regions.


## Technical Skills Demonstrated
*   **Data Transformation:** Cleaned and reshaped .csv data using Power Query.
*   **Data Modeling:** Star Schema design with optimized table relationships.
*   **DAX:** Created measures for YTD sales, Profit Margins, Return Rates etc.

## How to View the Report
*   Download the `Sales and Profitability.pbix` file to explore the interactive dashboard in Power BI Desktop.


