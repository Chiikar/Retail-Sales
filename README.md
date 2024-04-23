#### ![image](https://github.com/Chiikar/Retail-Sales/assets/156119801/4ee3ee0d-84cd-4c83-b0ef-62d01449d6d8)
# TATA-RETAIL-SALES-ANALYSIS



### DATA UNDERSTANDING 
This report presents a comprehensive analysis of TATA's retail data spanning from fiscal year 2010 to 2011, aiming to gain insights into customer transactions, sales patterns, and operational efficiency. Through exploratory data analysis (EDA) techniques, key findings and strategic recommendations have been identified to guide TATA's growth and optimization strategies.



### INTRODUCTION
The dataset utilized for analysis originates from TATA's retail store, encompassing customer transactions over the specified period. With 541,910 rows and columns including Invoice No, Stock code, Description, Quantity, Invoice Date, Unit price, column ID, and Country, the dataset provides valuable insights into TATA's retail operations.



### PROJECT GOAL 
The primary goal of the analysis is to gain a comprehensive understanding of customer transactions and sales patterns through EDA techniques. Specific objectives include identifying sales trends, analyzing top-selling products, exploring customer behavior insights, conducting geographic analysis, assessing operational efficiency, evaluating customer retention and loyalty, and identifying market expansion opportunities.


### DATA SOURCES 
The primary dataset utilized for this analysis is from TATA "Online-retail.xlsx" capturing sales transactions from the gadget store.


### TOOLS USED
- EXCEL: For data cleaning and analysis.
- POWER BI: For report creation.


### DATA CLEANING PROCESS
- The first thing I observed about my dataset is that it has 8 columns and 541,910 rows. 
- I checked for duplicates in my dataset and 5268 duplicates were found and removed, 536641 unique values remain. 
- I observed the data contains some returns to the store which are provided in negative quantities and there are unit prices that were input in error. So I created a check that the quantity should not be below 1 unit and Created a check that the Unit price should not be below $0 using Data validation. 
- Then I created another column for the revenue, which Is calculated by multiplying the quantity sold and unit price to give us the Revenue
- After the cleaning process the dataset has 9 columns and 536641 rows including the headers. 



### BUSINESS QUESTION BASED ON MY ANALYSIS OF THE CEO AND CMO
#### For the CEO:
1.	Profitability and Market Expansion: What are the top-selling products in terms of revenue, and which customer segments contribute the most to our profits? How can we leverage this information to expand our market reach or target new demographics effectively?
2.	Operational Efficiency: Are there any patterns or trends in sales data that indicate seasonality or fluctuations in demand? How can we optimize inventory management and supply chain processes to minimize stockouts, reduce carrying costs, and improve overall operational efficiency?
3.	Customer Retention and Loyalty: What is the customer churn rate, and are there any correlations between customer demographics, purchase frequency, and customer lifetime value? How can we enhance customer satisfaction, increase repeat purchases, and foster long-term loyalty among our customer base?
4.	International Expansion Opportunities: Which countries exhibit the highest growth potential based on sales performance and customer acquisition metrics? What market entry strategies can we employ to capitalize on these opportunities and expand our presence in lucrative international markets?


#### For the CMO:
1.	Marketing Effectiveness: What are the most effective marketing channels and campaigns in terms of driving sales and customer engagement? How can we allocate our marketing budget more efficiently to maximize ROI and achieve our sales targets?
2.	Product Assortment Optimization: Which product categories or Stock Keeping Units have the highest demand and profit margins, and are there any underperforming items that should be discontinued or repositioned? How can we optimize our product assortment to meet evolving customer preferences and stay ahead of competitors?
3.	Customer Segmentation and Targeting: Are there distinct customer segments based on purchasing behavior, demographics, or geographic location? How can we tailor our marketing messages and promotions to resonate with each segment and enhance personalized shopping experiences?
4.	Online vs. Offline Sales Performance: What is the contribution of online channels versus offline stores to overall sales revenue, and are there any differences in customer behavior or preferences between these channels? How can we integrate online and offline channels seamlessly to provide omnichannel shopping experiences and drive cross-channel sales growth?



### Exploratory Data Analysis 
1.	Time Series Analysis for Revenue (2011):
- Visualize monthly revenue trends for 2011 to identify seasonal patterns.
- Explore reasons behind seasonal trends to aid in future forecasting.
2.	Top 10 Revenue Generating Countries (Excluding UK):
- Display top revenue-generating countries and corresponding quantity sold.
- Exclude the United Kingdom from visualization to focus on other key markets.
3.	Top 10 Customers by Revenue Decline:
- Present a visual showing revenue decline from highest to lowest among the top 10 customers.
- Enable targeting of high-revenue customers to ensure satisfaction and retention.
4.	Demand Analysis Across Regions:
- Visualize demand for products across all countries to identify regions with high demand.
- Facilitate the CEO's expansion strategy by highlighting regions with growth opportunities.
- Ensure data presentation in a single view without the need for scrolling or hover interaction, excluding data for the United Kingdom.



### RESULTS 
1.	Total Revenue is $9,726,007 approximately $9.73M.
2.	Total Quantity Ordered is 5162502 approximately 5M worth of products.
3.	Total Product category is 4197.
4.	Total Countries with orders are 38.
5.	Total Customers are 401604. 
6.	According to the sales trend by month November 2011 has the highest sales in revenue of $1,456,145 which means November is their peak period.
7.	The top 10 countries with the highest sales are the United Kingdom, Netherlands, EIRE, Germany, France, Australia, Sweden, Switzerland, Spain, and Belgium. 
8.	The United Kingdom has the highest amount of sales.





### CONCLUSION
The analysis revealed significant sales trends, with November 2011 emerging as the peak period for revenue generation. The United Kingdom emerged as the primary market, closely followed by key regions like the Netherlands, EIRE, and Germany. Understanding customer behavior and optimizing operational processes are crucial for sustained success. Valuable insights into customer purchasing patterns and inventory management challenges were uncovered. Further exploration into metrics such as customer churn rate, purchase frequency, and lifetime value can enhance operational efficiency and customer satisfaction. Identifying top-selling products, profitable customer segments, and regions with high growth potential presents market expansion opportunities for TATA. Effective targeting of new demographics and maximizing revenue growth requires a deep understanding of customer preferences and market dynamics.




### RECOMMENDATION
1.	Profitability and Market Expansion: TATA should capitalize on insights regarding top-selling products and lucrative customer segments to extend its market presence. Tailored marketing campaigns and optimized product assortments can effectively engage new demographics and propel revenue growth.

2.	Operational Efficiency: Implementing strategies to optimize inventory management and supply chain processes is crucial. TATA should focus on minimizing stockouts, reducing carrying costs, and enhancing overall operational efficiency through advanced inventory management systems and demand forecasting techniques.

3.	Customer Retention and Loyalty: Elevating customer satisfaction, encouraging repeat purchases, and nurturing long-term loyalty require targeted initiatives. TATA should prioritize personalized shopping experiences, loyalty programs, and robust customer engagement strategies to enhance retention rates and maximize customer lifetime value.

4.	International Expansion Opportunities: TATA should prioritize markets demonstrating high growth potential based on sales performance and customer acquisition metrics. Tailored market entry strategies, aligned with each region's unique characteristics and preferences, are essential for successful expansion initiatives.

5.	Marketing Effectiveness and Product Assortment Optimization: Analyzing marketing channels and campaign efficacy can aid TATA in optimizing its marketing budget for maximum ROI. Additionally, identifying high-demand products and discontinuing underperforming ones can enhance profitability and customer satisfaction through an optimized product assortment.

6.	Customer Segmentation and Targeting: Identifying distinct customer segments based on purchasing behavior, demographics, and geographic location empowers TATA to tailor its marketing strategies accordingly. By delivering personalized shopping experiences and targeted promotions, TATA can drive sales growth and enhance customer satisfaction.

7.	Online vs. Offline Sales Performance: Seamless integration of online and offline channels is vital for providing omnichannel shopping experiences and driving cross-channel sales growth. TATA should invest in technologies and strategies to bridge the gap between online and offline sales channels, ensuring a cohesive shopping experience for customers.
