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
