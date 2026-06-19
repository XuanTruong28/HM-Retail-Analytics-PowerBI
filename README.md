# H&M Retail Analytics Dashboard (Data 2020)

## 1. Project Overview & Objectives
This project constructs a multi-dimensional analysis of customer behavior and business performance for H&M in 2020, utilizing a dataset of over 11 million transactions[cite: 5]. The dashboard translates operational data into strategic insights, focusing on revenue optimization, the role of personalization, and fashion product portfolio management[cite: 5].

* **Tools:** Power BI Desktop, DAX, Power Query.
* **Data Model:** Star Schema (Fact table linked to Customer, Product, and Time dimensions)[cite: 5].

## 2. Live Dashboard Interaction
[Click here to view and interact with the live dashboard](https://app.powerbi.com/groups/me/reports/80c3b30a-0823-4981-b3dd-5c29eed78680/3961f166d792b3042fc1?experience=power-bi)[cite: 5].

## 3. Dashboard UI & KPIs

### Page 1: Dashboard Overview (Operational Insights)
This page facilitates the monitoring of total operational performance, revenue structure by category, and performance comparisons between Online and Store channels[cite: 5].
* **Total Revenue:** 298.17K[cite: 5]
* **Total Transactions:** 11 Million[cite: 5]
* **Contribution:** 100% (Dynamic interaction based on selected segments)[cite: 5]

![H&M Overview Dashboard](HM-Retail-Analytics-PowerBI/overview.png)[cite: 5]

### Page 2: Dashboard Insights (Customer & Trends)
This page highlights the relationships between customer age, membership status, and aesthetic preferences[cite: 5].

![H&M Insights Dashboard](HM-Retail-Analytics-PowerBI/insight.png)[cite: 5]

## 4. Key Business Insights
* **Channel Performance (Online vs. Store):** Physical stores remain the primary revenue driver, exhibiting strong seasonality (peaking in April)[cite: 5]. The Online channel provides stable, supplementary revenue with more consistent growth trends toward the middle of the year (peaking in June)[cite: 5].
* **Product Portfolio Structure:** Revenue is highly concentrated in the **Ladieswear** segment (~47.5% of total revenue, approx. 141.62K)[cite: 5]. **Dresses** and **Trousers** serve as the anchor products driving segment sales[cite: 5]. The **Divided** segment contributes 21.1% with a diversified revenue structure, effectively boosting brand reach[cite: 5].
* **Membership Behavior:** **ACTIVE** members show high engagement (93.19% of the customer base) with 10.8 million total transactions, though they exhibit the lowest Average Order Value (AOV) (~0.027)[cite: 5]. Conversely, the **LEFT CLUB** segment displays the highest AOV (~0.031) but virtually zero transaction frequency[cite: 5].
* **Design & Aesthetic Preferences:** Treemap analysis reveals a clear dominance of **Solid patterns** and neutral color palettes like **Black, White, Beige, and Blue (Denim)**, confirming that commercial success is tied to minimalist, highly applicable designs[cite: 5].

## 5. Actionable Recommendations
1. **Secure Anchor Product Supply:** Establish higher Reorder Points and safety stock levels for Denim, Trousers, and Dresses within the Ladieswear segment to mitigate the risk of revenue loss due to stockouts[cite: 5].
2. **Pricing & Bundling Strategies to Boost AOV:** Leverage the high engagement of ACTIVE members by implementing bundle offers (e.g., "Trousers + Basic T-shirt") to increase basket value without compromising purchase frequency[cite: 5].
3. **Deepen Online Channel Strategy:** Transition from traffic-focused marketing to personalized product recommendations (focusing on basic colors and solid patterns) to improve conversion rates and optimize cross-channel engagement[cite: 5].

## 6. How to Use this Repository
* Download the original `.pbix` file.
* Open with **Power BI Desktop** to explore the Data Model structure and DAX measures utilized in the project.

## 7. Project Files
Due to GitHub's file size limits, you can access the full source structure and DAX formulas here:
[Download H&M_Retail_Analysis.pbix via Google Drive](https://drive.google.com/drive/folders/1AJkUCZzDpg1_H_Zqg1nIj_SbOa9eYvzG?usp=sharing)[cite: 5].

---
*Feel free to reach out via [truongxuan2834@gmail.com](mailto:truongxuan2834@gmail.com) for any discussion regarding this project.*
