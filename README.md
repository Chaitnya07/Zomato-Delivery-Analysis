![Sample Image](https://usenotioncms.com/proxy-prod/block/7aa08d67-759a-443e-aa07-376cbe7332ac/c5b09c36-a829-4cab-8c13-793616bf9d8a/0c6dd80e-bb72-49cb-94bf-9d9bea9c99b9/Desktop_-_10.png)

# Zomato-Delivery-Analysis with SQL (SQL Server)

This project involves an in-depth exploration and analysis of a Zomato dataset containing over 9000 rows of restaurant data, including information such as restaurant IDs, names, cities, locations, cuisines, and more. The goal is to gain a comprehensive understanding of the restaurant business as represented by the dataset.

## Data Exploration with SQL

During the data exploration phase, I performed the following tasks:

- **Table Structure Analysis:** Reviewed column names, data types, and constraints.
- **Duplicate Check:** Identified and removed duplicate values in the `RestaurantId` column.
- **Data Cleaning:** Removed unwanted columns to streamline the dataset.
- **Table Merging:** Merged two different tables to add a new `Country_Name` column using the `CountryCode` as the key.
- **Data Standardization:** Identified and corrected misspelled city names.
- **Rolling Count Calculation:** Used window functions to count the number of restaurants in a rolling/moving fashion.
- **Statistical Analysis:** Checked minimum, maximum, and average values for votes, ratings, and currency columns.
- **Rating Categorization:** Created a new column to categorize ratings for further analysis.

## Key Insights from Data Analysis

After processing the data with SQL, several insights emerged:

- **Geographical Distribution:** About **90.67%** of the data represents restaurants in India, with the USA accounting for **4.45%**.
- **Online Delivery Options:** Out of 15 countries, only India (28.01%) and UAE (46.67%) offer online delivery options.
- **Local Focus:** Since the dataset is heavily skewed towards India, further analysis focused on Indian restaurants.
- **Restaurant Density:** **Connaught Place, New Delhi** has the highest number of restaurants (122), followed by Rajouri Garden (99) and Shahdara (87).
- **Cuisine Trends:** North Indian food is the most popular cuisine in Connaught Place.
- **Table Booking Facilities:** Only 54 out of 122 restaurants in Connaught Place provide table booking facilities.
- **Rating Comparison:** Restaurants with table booking facilities have an average rating of **3.9/5**, compared to **3.7/5** for those without.
- **Top Restaurant Identification:** The best moderately priced restaurant (average cost for two < ₹1000, rating > 4, votes > 4) offering both table booking and online delivery, specializing in Indian cuisine, is identified as **'India Restaurant' in Kolkata, India (RestaurantID - 20747)**.

## Conclusion

This project demonstrates how SQL can be used to clean, explore, and analyze large datasets to extract meaningful business insights. By understanding the distribution, trends, and performance metrics in the Zomato dataset, we can derive actionable insights that can help inform strategic business decisions in the restaurant industry.

