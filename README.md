# Northwind Traders SQL Analysis

Summary: A comprehensive SQL analysis of the Northwind Traders database, exploring data insights through complex queries, joins and CTEs. This project involved analyzing sales revenue, customer behavior, suppliers, operational efficiency and logistics to derive actionable insights for business improvement.

## About the Project

### Collaborators
- Ayush Stephen Toppo
- Rhea Mall

### Tools Used
- **PostgreSQL** for database querying and analysis  
- **Jupyter Notebooks** for executing queries  

### Goals and Business Relevancy
Our goal was to analyze the Northwind Traders dataset to extract meaningful business insights related to **sales revenue, supplier behaviours, customer trends** and **operational efficiency**. By breaking down revenue trends and identifying patterns in purchasing behavior, high-value products, supplier reliability, and seasonal revenue fluctuations, we provide actionable recommendations to improve customer retention, optimize supplier partnerships and enhance logistics to maximize profitability.  

### Challenges
1. Incomplete or Empty Tables – The *customer_customer_demo* and *customer_demographics* tables are empty, limiting any demographic-based insights.
2. Identifying "Loyal Customers" and "At-Risk Customers" required defining clear business logic and thresholds. Ensuring meaningful segmentation based on available order history was a key challenge.
3. Some customers had inconsistent purchase histories, making it difficult to classify them into segments. This required careful handling of NULL values and missing timestamps.
4. Extracting meaningful insights required writing complex SQL queries involving multiple joins, subqueries, and aggregations. To improve readability and maintainability, Common Table Expressions (CTEs) were used.

## Actionable Insights

### Understanding Sales Revenue
1. The growth rate fluctuates consistently **(-40% to 60%)** throughout the period. The sharp decline between **1998-01 and 1998-04** suggest the need for a more proactive approach in forecasting and managing sales trends. The company can develop advanced predictive models to anticipate and mitigate potential sales issues.  
2. There’s a clear divergence between total sales and growth potential. **Margaret Peacock** leads in sales but shows signs of plateauing, while **Laura Callahan’s** strong growth rate suggests future potential.  To capitalize on current success, top performers like Margaret, should be supported but provided opportunities to boost her growth. The company can focus on nurturing and supporting individuals like Laura Callahan who show strong growth potential. This could include offering mentorship or some additional resources.

### Supplier Data Analysis 
1. Most suppliers (21 out of 29) offer three or fewer products, making niche suppliers valuable if their products meet specific market needs. However, categories like **Beverages, Seafood, and Meat/Poultry** rely on single-product suppliers, posing a supply risk. Encouraging **diversification or securing alternative suppliers** can mitigate this risk.  
2.  The results reveals that **Plutzer Lebensmittelgroßmärkte AG, Specialty Biscuits, Ltd.**, and **Pavlova, Ltd.** are the top suppliers in terms of total sales volume. They should be given additional focus in negotiations to secure favorable terms for long term partnerships to ensure supply continuity. Additionally, suppliers offering multiple high-priced items, like Pavlova Ltd. and Plutzer Lebensmittelgroßmärkte AG could be key partners for expanding the luxury product range of the company. Focusing on premium products alongside the current assortment may boost overall sales in the high-value segment.

### Customer Data Analysis
1. **Save-a-lot Markets, Ernst Handel** and **QUICK-Stop** are the top 3 customers, with the largest order size and the maximum total spend. The company could introduce tiered rewards or special bulk purchase incentives to further increase repeat orders from them. Understanding what these customers frequently purchase can help in tailoring personalized recommendations or bundling complementary products to enhance their purchasing experience.
2. There are five customers at risk, who haven't placed orders in the past six months. A **targeted re-engagement strategy** is essential. Personalized outreach through emails or calls, offering limited-time discounts or special promotions based on their previous purchase history, could help reignite their interest. The company could also investigate and address potential reasons behind their inactivity (pricing, competition, or changing business needs).
3. With most orders concentrated in winter and early spring, i.e. **January to April**, the company should focus on sustaining revenue during these peak months while finding ways to mitigate the seasonal dip in summer. One approach could be launching limited-time promotions or introducing summer-specific product bundles to attract more sales in off-peak months.

### Operational Efficiency
1. Only 7.61% of delayed orders were due to **stockouts**. This indicates that stockouts are not the primary bottleneck. Other factors like shipping inefficiencies or employee processing delays likely play the biggest role.
2. From the 9 employees, **Steven** has processed the least number of orders and also has the lowest average processing time. However, out of 42 orders, he only has 1 delayed order - this means his quality of work is higher. On the other hand, **Anne** may need more training/support, since she has the highest % of delayed orders and thus the lowest processing time, even though she has processed the same number of orders as Steven (42).
3. Out of all the shippers, **United Package** is the slowest, taking the most amount to time for delivery, and is also the most costly on average. Since they handle the bulk of orders, it might be worth negotiating better shipping contracts with them to significantly reduce costs. Additionally, **Speedy Express** has the lowest shipping costs per order. If expediting deliveries with Speedy Express can further improve order fulfillment without significantly increasing costs, shifting more shipments to them might be a good idea because customer satisfaction is often affected by long wait times.

# Conclusion 

Our analysis provided valuable insights. Key findings highlighted growth opportunities for underperforming employees, risk mitigation strategies for supplier dependencies and operational improvements for logistics and order fulfillment.

By leveraging these insights, Northwind Traders can implement data-driven strategies to boost revenue, improve supplier partnerships, enhance customer retention and improve operations. Future work could involve integrating predictive analytics to forecast sales trends and optimize inventory management further.
