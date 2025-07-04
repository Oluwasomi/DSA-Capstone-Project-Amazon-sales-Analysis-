# DSA-Capstone-Project-Amazon-sales-Analysis-

## Prohect Topic: Amazon Product Analysis

### Project Overview
This project involved exploring a dataset of 1,465 Amazon-listed products, cleaning the data, building calculated columns, answering key business questions using PivotTables, and presenting the results in an interactive Excel dashboard.

### Data Source
The primary data source used here is the Amazon sales data for the purpose of this project Analysis.

### Tools and Techniques used

1. Microsoft Excel[Download here](https://www.microsoft.com/en-us/microsoft-365/excel)
- Data Cleaning
  -  removed nulls, fixed types, handled missing values
- Data Transformation
  -  calculated discount %, revenue, buckets
- PivotTables
  -  used to summarize discount averages, review totals, price comparisons
  -  Dashboard
  -  interactive layout using charts and visuals

### Data Cleaning and Preparation

To ensure accurate and meaningful analysis, the dataset underwent the following data cleaning and transformation steps in Microsoft Excel:

1. Removed rows with missing essential values such as `actual price`, `discounted price`, or `rating`.
Filled or corrected  null or improperly formatted fields, including:
  -  Stripping currency symbols (₹) from price columns
  -  Ensuring rating counts and prices were in numeric format
2. Created new calculated columns to enhance analytical capability:
 -  Discount Percentage
  `= (Actual Price - Discounted Price) / Actual Price × 100`
    To identify how heavily products are being discounted
  -  Potential Revenue
  `= Actual Price × Rating Count`
 To estimate potential sales volume per product
  -  Price Buckets
  Grouped products into categories:
< ₹200
₹200 – ₹500
> ₹500
  -  For pricing strategy insights
  Rating Range Bucket
  Categorized average ratings into:
 0–1, 2–3, 3–4, 4–5 
3. Ensured  consistent naming of product categories (e.g., avoiding variants like “Home & Kitchen” vs “Home and Kitchen”).
Cleaned product names for readability in dashboard visuals.
4. Pivot Table creation (e.g., category vs average discount)
5. Dashboard Creation

### Exploratory Data Analysis

1. Which category has the highest average discount?
2. How many products are in each category?
3. Which categories have the highest total reviews?
4. Which products have the highest average ratings?
5. What is the average actual vs discounted price by category?
6. Which products have the highest review counts?
7. How many products offer ≥50% discount?
8. What’s the overall product rating distribution?
9. What is the revenue potential by category?
10. How are products distributed across price ranges?
11. Does discount level correlate with product rating?
12. How many products have fewer than 1,000 reviews?
13. Which category contains the highest-discounted products?
14. What are the top 5 products based on rating × review count?

### Analysis Insights

1. Home Improvement has the highest average discount (58%), followed by Health & Personal Care and Computers & Accessories.
2. Electronics and Home & Kitchen categories dominate in product count and review volume
3. Electronics leads in revenue potential (₹91B+), making it the highest-value category.
4. Several AmazonBasics and boAt products are among the most-reviewed and highest-rated.
5. 662 products offer discounts of 50% or more.
6. Majority of products are rated between 4–5 stars; very few products fall below 3.
7. 310 products have fewer than 1,000 reviews — an opportunity for promotional focus.
8. No strong correlation between high discount and high rating.

### Data Analysis

![image](https://github.com/user-attachments/assets/5b037e55-9faa-4ff0-9029-f27ed545fd44)
![image](https://github.com/user-attachments/assets/9536654b-eba8-4a80-81d3-e5d2ddb7538d)
![image](https://github.com/user-attachments/assets/8c57e062-0056-444e-baef-2f7d536ecbd0)
![image](https://github.com/user-attachments/assets/acdd89ec-570d-4149-b6dd-2ba4dac65a4e)
![image](https://github.com/user-attachments/assets/c8d321ed-1ad2-4277-9c0b-cbdaace3b096)
![image](https://github.com/user-attachments/assets/80649eb5-fc4b-4aa0-bd76-66884f09e474)
![image](https://github.com/user-attachments/assets/9aafde96-1d7f-49b0-8770-44c29e6d2e7c)
	
### Summary of key Findings

-Product Count and Revenue
  -  Home & Kitchen has many products but generates far less revenue than Electronics.
  -  High Discounts May Hide Poor Quality
Deep discounting in categories like Home Improvement doesn't always align with high ratings.
- Underserved Categories
  -  Office Products and Musical Instruments are lightly populated — potential for expansion.
- Review Count Strategy
  -  310 products with low reviews should be targeted for promotions to boost engagement.
- Customer Loyalty Gaps
  -  Some highly reviewed products have average ratings — bundle or replace with better-rated options.

### Recommendations

1. Electronics and Computers & Accessories generate the highest potential revenue.
These should be prioritized in advertising, inventory, and bundling strategies.
2. Categories with high discounts but moderate or low ratings (e.g., Home Improvement) may require quality or packaging review.
Avoid excessive discounting without addressing customer complaints.
3. Over 300 products have fewer than 1,000 reviews, these should be targeted for campaigns, promotions, or customer engagement incentives (e.g., loyalty points for reviews).
4. Majority of products fall into the ₹200–₹500 range, indicating a price-conscious market.
Consider value packaging, bundles, or tiered pricing for budget-conscious customers.
5. Products with high reviews but average ratings (e.g., 3–3.5 stars) may need further investigation.
Use sentiment analysis or text reviews to understand dissatisfaction drivers.

### Limitations

- Some products had missing prices, ratings, or review counts and were excluded, which may slightly bias category-level insights.

- Analysis was conducted at the product level only.
No customer segmentation, location, or behavior data was available.

- The data represents a static snapshot and doesn’t account for how reviews or ratings may change over time (e.g., product updates, seasonal spikes).
