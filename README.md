# Amazon-Product-Review
MY FIRST EXECUTED PROJECT WITH DSA INCUBATOR
# The Journey

**Data Source**
The dataset was downloaded from the DSA Canvas . It contains product reviews, ratings, pricing, and metadata.

**Product Reviews Data Cleaning & Processing**
This project focuses on cleaning and preprocessing a dataset of product reviews and ratings obtained from the DSA Canvas LMS. The goal was to prepare the data for further analysis by ensuring consistency, removing redundancies, and enhancing usability and ultimately proceed to pivoting for exploratory data analysis.

**Note**
This project assumes that each product should have a unique entry.
Blank rows and irregular pricing data were carefully handled to maintain data integrity before proceeding to pivoting to provide solutions to analytical tasks.

**Tools Used**
- Microsoft Excel for:
 - Data Collection
 - Data Cleaning
    - Data Manaipulation
    - Data Munching
 - Data Analysis
   - Pivot Tables
   - Calculated Columns

 **Data Cleaning Summary**
Initial Cleaning
**Removed Empty Rows/Columns:**
- Dropped rows and columns that contained only missing values.
- Standardized Column Names: Stripped whitespace from column headers for consistency.

**Deduplication**
- Removed 114 duplicate entries based on product_id.
- Assumption: Each product should have only one record since the dataset is focused on reviews and ratings.

**Categorization**
Products were categorized into Level 2, Level 3, and Level 4 categories for hierarchical analysis.

**Revenue Estimation**
Corrected irregular figures in the actual_price column.
Created a new column: total_potential_revenue, calculated based on available pricing and rating data.

**Exploratory Data Analysis**
 EDA involves performing tasks to answer questions posed towards in the course of the analysis, viz:
- What is the average discount percentage by product category?
- How many products are listed under each category?
- What is the total number of reviews per category?
- Which products have the highest average ratings?
- What is the average actual price vs the discounted price by category?
- Which products have the highest number of reviews?
- How many products have a discount of 50% or more?
- What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
- What is the total potential revenue (actual_price × rating_count) by category?
- What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
- How does the rating relate to the level of discount?
- How many products have fewer than 1,000 reviews?
- Which categories have products with the highest discounts?

-  This hands-on project helped me explore:
 - How discount levels impact potential revenue
 - Category performance and product pricing distribution
 - Rating patterns and customer review volumes
 - Custom formulas for discount buckets, revenue estimation, and scaling factors

 ## Key Insights & Conclusion:
- High discounts (≥50%) tend to boost visibility and purchase likelihood.
- Categories like Electronics and Computers show strong performance in ratings and potential revenue.
- Customer reviews and ratings play a vital role in scaling product value
- Products with Fewer than 1,000 Reviews: 310 — could indicate new listings or low-performing products.
- Rating vs. Discount: No direct correlation shown — implies customer satisfaction might not always depend on discount level.
- Review-to-Product Ratio: Categories like Office Products and Health & Personal Care have fewer reviews despite high discounts — a sign of possible low visibility or relevance.


## Recommendations:
 - Focus discounts on underperforming or overstocked products to drive engagement.
 - Promote highly-rated products as category flagships.
 - Improve product quality and review volume in low-rated categories.
 - Use structured discount buckets to optimize pricing strategies.

Every row of data told a story, and every formula revealed a new perspective — I’m excited to keep building on this momentum!
