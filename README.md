# Amazon Sales Analysis
# Table of contents 
- [Project overview](#projectoverview)
- [Data sources](#datasources)
- [Recommendations](#recommendations)

### project overview 


The Amazon Sales Analysis is a comprehensive data analytics project developed to provide a clear visualization and understanding of sales performance across different product categories on Amazon. The project focuses on deriving actionable insights from raw transactional data to support informed business decisions regarding product pricing, marketing, and inventory management.

The dashboard was built using Power BI, integrating data transformation, modeling, and visualization techniques. It enables users to analyze trends in sales revenue, discounts, savings, product ratings, and category performance.


<img width="840" height="479" alt="amazon sales dashboard" src="https://github.com/user-attachments/assets/3b275d27-3e93-4ad4-80eb-4d1fe06826ce" />


### Data sources 

The dataset used in this project was obtained from Quantum Analytics NG.

### Tools 
- Power Bi - incorporating data cleaning, transformation and visualisation techniques

### Data cleaning/preparation 

1. Data inspection.
2. Handling mising values.
3. Removing duplicates.
4. Data type correction.
5. Creating calculated columns using DAX function.
6. Standardize naming and formats.
7. Remove outliers.
8. Validate and load the final clean data into Power BI.

### Exploratory Data Analysis

- What is the total Actual Price and Discounted Price across all products?
- What is the average discount percentage applied across the dataset?
- How are product ratings distributed from (1 to 10 )?

  
### Data Analysis

``` Dax function 
Total savings = [total actual price] - [total discounted price]
```

## Result/finding 

The analysis results are summarized as follows:
- ## Overall Sales Performance

   - The Total Actual Price (sum of all pre-discount prices) amounted to approximately ₦1 million, while the Total Discounted Price was ₦615K, indicating a total   customer savings of about ₦403K.
   - The Average Actual Price per product was ₦2.21K, and the Average Discounted Price was ₦1.34K, representing an average discount rate of 39.57%.
   -  Insight: These figures suggest that discounts play a major role in driving customer purchases on Amazon.

- ## Category Performance
  
  - Home & Kitchen emerged as the highest-performing category, generating the largest share of total sales and discount amounts.
  - Computers & Accessories ranked second, showing strong sales figures and customer interest.
  - Electronics came third, with fewer items but higher average prices.
  - Categories like Office Products and Musical Instruments contributed smaller portions of sales but showed consistent customer satisfaction levels.
  - Insight: The dominance of Home & Kitchen products indicates higher consumer demand for household and everyday-use items.

- ## Discount and Pricing Insights
   - Products across categories had significant discounts ranging from 10% to 60%, with an average of nearly 40%.
   - Categories with larger discounts (especially Home & Kitchen and Electronics) tended to have higher total sales volume.
   -  A clear pattern emerged where discounts positively influenced sales — products with greater discounts received more attention and ratings from customers.
   - 📉 Insight: The data suggests that strategic discounting is effective for increasing both visibility and sales on Amazon.

- ## Product Ratings and Customer Engagement
  - The average product rating across the dataset was 3.9 out of 5, reflecting generally positive customer experiences.
  - Most products received ratings of 4.0 and above, indicating high overall satisfaction.
  - Products with more discounts tended to receive a higher number of ratings, possibly due to increased purchase volume.
  - Insight: Customer satisfaction is strong across top-performing products, and discount-driven purchases often translate to more reviews and feedback.


### Recommendations

- Implement data driven discount policies  use dashboard insights to identify which products respond best to discounts and adjust offers accordingly.
- Allocate more budget to digital marketing and Amazon-sponsored ads targeting high performing categories.
- Use these best-performing products in cross selling and bundle offers to increase exposure for lower performing products within the same category.
- Conduct targeted promotional campaigns to raise awareness.
- Use ongoing Power BI analysis to track price changes vs. sales volume and identify optimal pricing points.
- Schedule weekly or monthly reviews using the dashboard to track performance and adjust strategies dynamically.







