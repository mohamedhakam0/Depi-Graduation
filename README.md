# Depi-Graduation (Real Estate Analysis)
this Repo has my graduation project for DEPI 
This project analyses the Egyptian real estate market using a dataset obtained from Kaggle. The goal is to identify trends and patterns in property prices, locations, and features to provide insights into the market landscape and help individuals make informed real estate decisions.
Data Cleaning and Preparation:
The raw dataset required cleaning and transformation to ensure accuracy and consistency. Several steps were taken using Microsoft Excel and Power Query, both in Excel and Power BI:
●
Region Mapping: A new column for "Region" was added. Using Power Query, duplicate city names were removed, and each unique city was manually assigned a region. This was achieved through data validation in Excel and a merge query in Power BI.
●
Data Accuracy: The "Fill Down" method was used to fill in any blank cells in the region column. Spelling errors and inconsistencies in data entries were corrected through replaced values.
●
Data Type Conversion: Data types for various columns were changed for improved accuracy and analysis.
●
Column Renaming: Columns were renamed to be more understandable.
●
Index Column Addition: An Index column was added to count the total number of property offers.
●
Data Filtering: Rows with unknown or inaccurate data were filtered out to improve the dataset's reliability.
●
Delivery Date Estimation: Missing delivery dates were estimated based on the "Delivery Term" column. If the delivery term was "Finished," the year was set to 2024. For other delivery terms, the years were estimated to be between 2026 and 2027.
Data Analysis and Visualisations:
The cleaned data was analysed using Microsoft Power BI to create a dynamic dashboard. Various charts and measures were used to visualise and understand the data, revealing key insights into the Egyptian real estate market:
Key Insights:
●
Price Influencers: Property types, location, and features significantly influence prices. For example, standalone villas have the highest average price, East Cairo is the most expensive region, and furnished and finished properties command higher prices.
●
Demand Trends: Apartments and chalets are the most common property types, suggesting high demand. A peak in property deliveries is expected in 2024, potentially indicating future market shifts.
●
Payment Preferences: Cash payments are the dominant payment method in the market.
●
Furnishing Status: Non-furnished properties are significantly more prevalent than furnished properties.
Conclusion:
The analysis highlights important trends in the Egyptian real estate market, such as the dominance of East Cairo in terms of price and the popularity of specific property types. The insights derived from this project can be valuable for both buyers and sellers in making informed decisions.
Repository Contents:
●
Cleaned dataset
●
Power BI dashboard file (.pbix)
●
Documentation on data cleaning and analysis steps
Future Work:
●
Expand the analysis to include more variables and data points.
●
Develop predictive models to forecast future market trends.
Please note that while the insights provided are valuable, they are specific to the dataset used and the time period analysed. Market conditions can change, so it is important to stay updated on current trends.
