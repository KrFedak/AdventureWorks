# Adventure Works: Sales & Profitability Audit

## Project Overview
This Power BI dashboard provides a comprehensive audit of sales performance for the fictional company **Adventure Works**. The analysis covers data from **January 2020** to **June 2022**, transforming raw data from the Kaggle repository into actionable insights.

The report is structured into three dedicated pages, each specifically designed to address a core business category: **Net Executive Performance, Pdroduct Quality Audit, and Customer Value**. This ensures a focused approach to operational efficiency and data-driven decision-making.

<img width="1347" height="758" alt="image" src="https://github.com/user-attachments/assets/c5b1195b-dc93-41f9-b52d-560da236d4c2" />


## Technical Skills Demonstrated
*   **Data Transformation:** Cleaned and reshaped .csv data using Power Query.
*   **Data Modeling:** Star Schema design with optimized table relationships.
*   **DAX:** Created measures for YTD sales, Profit Margins, Return Rates etc.

## How to View the Report
*   Download the `Sales and Profitability.pbix` file to explore the interactive dashboard in Power BI Desktop.

# Executive Insights: Addressing Key Business Questions

## 1. Financial Health & Profitability

**Question:** What is our true Net Profit after accounting for returns and inventory recovery?

<img width="460" height="228" alt="image" src="https://github.com/user-attachments/assets/f5462a5e-b53f-4c14-a304-4a5d12b33083" />
<br>
<img width="647" height="252" alt="image" src="https://github.com/user-attachments/assets/42809ba3-984c-41fc-81b6-471d103e2155" />
<br>

*   **Exceptional Stability:** The company’s performance is exceptionally stable. The net profit margin has consistently remained above 40% throughout all analyzed years, demonstrating excellent cost control even during periods of rapid revenue growth.

*   **Margin Protection:** Net Profit was stabilized by identifying and removing high-return/low-volume products that were causing operational losses.
  
*   **Expansion Impact:** Adding new product categories significantly grew the customer base and increased total profit.

*   **Actionable Insight:** Some items, like "Mountain-500" bike, require further review due to its high return rate.

## 2. Quality Control & Regional Performance

**Question:** Which categories drive return rates and how does this affect growth?

<img width="460" height="228" alt="image" src="https://github.com/user-attachments/assets/05a8f2a3-6504-49cd-b15a-2bf3e8f1f5cf" />
<br>
<img width="641" height="313" alt="image" src="https://github.com/user-attachments/assets/d37a9aab-857b-40db-9b81-5ef3f21de63d" />
<br>

*   **Product Risk:** High return rates in specific bike models are the primary drag on YoY growth, as they generate 13 times more profit than two other categories combined. Although return rate of bikes is decreasing from year to year. Other items that need further examination - **Shorts, Vests**. Expanding "one-product" categories (e.g., Hydration Packs, Bike Racks) is recommended to diversify risk. 
   
*   **Canada (High Volume):** Customers buy often but spend less per order, mainly focusing on accessories.

*   **Strategy:** Focus on converting these loyal buyers into first-time bike owners.

*   **USA (Market Leader):** This is the largest market, but it has low revenue per customer and high churn (customers leaving).

*   **Strategy:** Use an Upselling Strategy for premium bikes to improve the regional ROI.

*   **Australia (Efficiency Model):** Australia is the most efficient market, producing high revenue with only half the customer base of the USA. This high-loyalty model should be the benchmark for other regions.

## 3. Customer Retention & Growth

**Question:** How effective is our customer conversion and Revenue per Member?

*   **The Retention Gap:** While acquisition is high, new growth is outpacing loyalty. This has caused the average Revenue per Member to drop as the database grows without repeat purchases.

*   **The 5% Rule:** Improving retention for our 18,000+ members by just 5% is more profitable than aggressive expansion into new markets.

*  **Recommendation:** Launch a "Welcome Back" program and loyalty rewards to re-engage inactive members.

