# Amazon-Product-Review
MY FIRST EXECUTED PROJECT WITH DSA INCUBATOR

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
