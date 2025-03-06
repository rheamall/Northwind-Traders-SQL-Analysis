# Business Intelligence Analysis of the Northwind Traders Database

**Summary**: This is a comprehensive SQL analysis of the Northwind Traders database, a simulated dataset commonly used for learning and business intelligence exploration. We explored data insights through complex queries, joins and CTEs. Our analysis was focused on 4 key areas: **sales revenue, customer behavior, suppliers** and **operational efficiency**, to derive actionable insights for business improvement.

## About the Project

### Data Source
https://github.com/pthom/northwind_psql/tree/master 

### Collaborators
- Ayush Stephen Toppo
- Rhea Mall

### Tools Used
- **PostgreSQL** for database querying and analysis  
- **Jupyter Notebooks** for executing queries  

### Goals and Business Relevancy
Our goal was to analyze the Northwind Traders dataset to extract meaningful business insights related to **sales revenue, supplier behaviours, customer trends** and **operational efficiency**. By breaking down revenue trends and identifying patterns in purchasing behavior, high-value products, supplier reliability, and seasonal revenue fluctuations, we aimed to provide actionable recommendations to improve customer retention, optimize supplier partnerships and enhance logistics to maximize profitability.  

### Challenges
1. The *customer_customer_demo* and *customer_demographics* tables were empty, limiting any demographic-based insights.
2. Ensuring meaningful segmentation based on available order history was a key challenge we faced. For example, identifying "Loyal Customers" and "At-Risk Customers" required defining clear business logic and thresholds. 
3. Some customers had inconsistent purchase histories, making it difficult to classify them into segments. This required careful handling of NULL values and missing timestamps.
4. Extracting meaningful insights required writing complex SQL queries involving multiple joins, subqueries and aggregations. To improve readability and maintainability, we used Common Table Expressions (CTEs).

## Key Actionable Insights

### Understanding Sales Revenue
1. The growth rate fluctuated consistently **(-40% to 60%)** throughout the period. The sharp decline between **1998-01 and 1998-04** suggested the need for a more proactive approach in forecasting and managing sales trends. The company can develop advanced predictive models to anticipate and mitigate potential sales issues.  
2. There was a clear divergence between total sales and growth potential. **Margaret Peacock** was leading in sales but showed signs of plateauing, while **Laura Callahan’s** strong growth rate suggested greater future potential.  To capitalize on current success, top performers like Margaret should be supported and provided opportunities to boost her growth. The company can also focus on nurturing and supporting individuals like Laura Callahan who show strong growth potential. This could include offering mentorship or some additional resources.

### Supplier Data Analysis 
1. Most suppliers (21 out of 29) offered three or fewer products, making niche suppliers valuable if their products met specific market needs, but also posing a supply chain risk. Encouraging **diversification or securing alternative suppliers** can mitigate this risk.  
2. The results also revealed that **Plutzer Lebensmittelgroßmärkte AG, Specialty Biscuits, Ltd.**, and **Pavlova, Ltd.** were the top suppliers in terms of total sales volume. They should be given additional focus in negotiations to secure favorable terms for long term partnerships to ensure supply continuity. Additionally, these 2 suppliers also offered multiple high-priced items, so they could be key partners for expanding the luxury product range of the company which may boost overall sales in the high-value segment.

### Customer Data Analysis
1. **Save-a-lot Markets, Ernst Handel** and **QUICK-Stop** were the top 3 customers, having the largest order size and also the maximum total spend. Understanding what these customers frequently purchase could help in tailoring personalized recommendations or bundling complementary products to enhance their purchasing experience.
2. There were five customers at risk, who hadn't placed orders in the past six months. A **targeted re-engagement strategy** is therefore essentia, which may include offering limited-time discounts or special promotions based on their previous purchase history to reignite their interest. 
3. With most orders concentrated in winter and early spring, i.e. **January to April**, the company should focus on sustaining revenue during these peak months while finding ways to mitigate the seasonal dip in summer. One approach could be launching limited-time promotions or introducing summer-specific product bundles to attract more sales in off-peak months.

### Operational Efficiency
1. Only 7.61% of delayed orders were due to **stockouts**. This indicated that stockouts were not the primary bottleneck. Other factors like shipping inefficiencies or employee processing delays likely play the biggest role.
2. Out of all the 3 shippers, **United Package** was the slowest, taking the most amount to time for delivery, and was also the most costly on average. Since this shipper handles the bulk of orders, it might be worth negotiating better shipping contracts with them to significantly reduce costs. Additionally, **Speedy Express** had the lowest shipping costs per order and also faster delivery times. Shifting more shipments to them would not only reduce costs but may also improve customer satisfaction, which is often affected by long wait times.

# Conclusion 

Our analysis provided valuable insights. Key findings included identifying high-value customers, high-performing employees, peak order months and operational improvements for logistics and order fulfillment.

By leveraging these insights, Northwind Traders can implement data-driven strategies to boost revenue, improve supplier partnerships, enhance customer retention and improve operations. Future work could involve integrating predictive analytics to forecast sales trends and optimize inventory management further.

## Feedback is welcome. Connect with us:
[Rhea:](https://github.com/rheamall)
- Linkedin: https://www.linkedin.com/in/rheamall
- Email: rheadeepamall@gmail.com
