# Technical Report for Prestige Superstore Sales Analysis (2015–2018)

# 1.	Outline

▪️Introduction

▪️Story of Data

▪️Data Splitting and Preprocessing

▪️Pre-Analysis

▪️In-Analysis

▪️Post Analysis and Insights

▪️Data visualization and Charts

▪️Observations and Recommendations

▪️References

# 2. Introduction

 <img width="975" height="424" alt="image" src="https://github.com/user-attachments/assets/92944e26-9e99-48ac-9da9-e5203d115c73" />

This report looks at sales data from 2015 to 2018 across the Central, Eastern, Southern, and Western regions. It explores which products performed best, how customer spending varied, and where the strongest sales came from. By spotting patterns and regional differences, the goal is to help guide smarter decisions around what products to stock, where to focus marketing efforts, and how to grow sales more effectively in the future.

Key Datasets and Methodologies: The dataset used is a sales data and was analyzed using pivot tables in Microsoft excel.

# 3. Story of Data

Data Source: The dataset used is publicly sourced from Kaggle.com

Data Structure: The dataset is organized in rows representing transaction records and columns containing different attributes such as Order Date, Product Category, Segment, Sales, Ship Mode, States, etc.

Story of Data: The data is telling a story around goods related to office supplies sold by the firm situated in different states of the USA for the period of four years, this also highlighting different product categories and subcategories sold, the ship mode used for shipping and also including the customers who made the purchase.

# 4. Data Splitting and Preprocessing

Data Cleaning: The dataset was pre-cleaned, containing no missing values, empty rows, or duplicate records. To enhance readability and presentation, the cell sizes were adjusted accordingly, and the data was formatted as a standardized Excel table.

Data Transformation: During the data transformation process, a new columns was appended to enhance the analysis. These included Month Year of Order, derived from the Order date using the TEXT formula.

Data Splitting: The dataset was divided into two main categories using a data split approach to make it easier to explore specific areas of the data and answer key questions.

1. Category One — Independent value

Product Name

Category

Sub-category

Region

State

City

Segment

Customer Name

Ship Mode

Order Date

2. Category Two — Dependent value

Sales

Industry Context: The data pertains to the retail industry with particular relevance to office supply stores, and the analysis aims to identify sales trends and patterns to support revenue growth.
Stakeholders: The key stakeholders of this project include the Chief Executives, Sales Managers, and the Marketing Team.
Value to the Industry: Revenue growth is widely considered a primary measure of value in the retail industry, and is often used to define overall success.

# 5. Pre-Analysis

Establishing a clear understanding of the key questions to address and the types of potential analysis to perform is essential for providing direction and maximizing the effective use of the data. This formed a critical component of the pre-analysis phase, ensuring that the analysis remained focused and aligned with the overall business objectives. The primary areas identified for potential analysis are outlined below.

1. Regional performance by amount sold

2. Best performing product over the years by how much it sold

3. Customer performance analysis by sales

4. Performance analysis of each segment over the years by sales

5. Product category performance by sales

6. Performance analysis of the Ship mode with reference to the sales

7. State performance by sales

8. Performance analysis of each city by sales

9. Sales trend performance report over the years

10. Time lag analysis between order date and the ship date with reference to sales

11. Best performing product sub-category by sales

12. Best performing city per state over the years by their sales

13. Product performance analysis by unit price and profit generated

14. Regional performance analysis by overall sales over the years

15. Customer performance analysis with reference to city and sales over the years

16. Profit analysis by product category

17. Customer preferred ship mode over the years

18. Customers preferred payment type by profit generated

19. Best performing ship mode of the year by count of goods Delivered

20. Analyze the best preforming year by sales

21. Analyze the best preforming state by sales

Initial Insights

1. Finetune the best region for each year and implement more measures to gain more ground against competitors e.g. more ads.

2. Finetune out the best performing product and ensure this product never diminishes by stocking more hence preventing its customer base from switching.

3. Finetune least performing region and implement methodologies used at the top performing regions to ensure revenue means.

4. Finetune out the best customer for each year and ensure to consider them for special bonuses.

5. Finetune out the least performing customers and consider them for some incentives whenever they made purchase to encourage them to buy more.

6. Finetune out the least performing product of the year and consider a massive sell out event such as black Friday where the prices of this product will be slash down and more sales made.

7. Finetune out the best ship mode overtime and ensures it is always readily available for customers use.

8. Finetune out the best performing months for each year and ensure methodologies are implemented in future sales

9. finetune out the least performing month of the year and implement strategies used in the months with high sales.

10. Finetune out the best product category of the year and ensures it never runs out of stock to prevent customers from looking out hence keeping the revenue stable

11. Finetune out the bet performing state and ensure more product are shipped there.

12. Finetune out the lowest performing states and ensures more salespersons are move there for more sales.

13. Finetune out the best performing city and state and consider setting up more outlets around the city and reducing or eliminating customers base shipping fee hence more customers and more revenue.

14. Finetune out the least performing city and state and consider implementing strategies use in the top performing city for improvement hence generating more revenue.

15. Finetune out profit made by each category of product to understand the category that requires more investment and do so.

16. Finetune out the best performing ship name of the year and consider an award for the ship to solidify relationship hence preventing it from absconding.

# 6. In-Analysis

Unconfirm Insights

▪️Technology lead the product category with $827,455.87 sales followed by Furniture with $728,658.58 sales, whereas Office supplies is the lowest with $705,422.33 sales.

▪️California tops as the best performing state with sales of $446,306.46 while North Dakota is the lowest among the top ten with $919.91 sales.

▪️ The top three product sub-category include phones leading with $327,782.45 sales, followed by chairs with $322,822.73 sales and storage with $219,343.39 sales. while the lowest in top ten is Appliances with $104,610.48 sales.

▪️Among the three segment, the Consumer segment leads with $1,148,050.53 followed by Corporate with $688,494.07 and, Home Office with $424,928.18 sales.

▪️Western region lead the regional sales with $710,219.68 followed by the Eastern region with $669,518.73, and Central region with $492,646.91. The Southern region made the lowest sales of $389,151.46.

▪️Sean miller top the customers chart with $25,043.05 purchases while Christopher Conant is the lowest of the top ten with $12,129.07 purchase.

▪️The highest sales of $722,052.52 was recorded in 2018, followed by $600,192.55 in 2017, meanwhile in 2015, $479,856.21 sales was made and the lowest year sales was $459,436.01 recorded in 2016.
Recommendations

▪️More investment is recommended for all categories, with more consideration on the technology which sells more.

▪️Investigate the reasons for low sales in states such as Wyoming, South Dakota, Maine, West Virginia, and especially North Dakota and implement the strategies used in the top performing states like California to improve future sales.

▪️Consider more inventory on phones and chairs to prevent the customers base from shrinking.

▪️Stock more of the consumers goods for to make more sales.

▪️31.40% of the total sales made is from the Western region hence an expansion into more cities in the West should be consider.

▪️The top three performing customers should be consider for a company’s discount on all purchases.

▪️Analyze and implement the measures contributing to the linear increase of sales from 2016 to 2018 for future sales.

Analysis Techniques Used: To make the data easier to analyzed more efficient, a pivot table was used to quickly summarize and explore the dataset. This tool makes it easy to group, filter, sort, and perform calculations like totals, averages, and counts.

# 7. Post-Analysis and Insights

▪️The central region has a total sales of $492,646.91 between 2015–2018. The product categories sold in this region are technology making the highest sales of 34.25%, office supplies 33.21% and furniture 32.54%. Among the top ten customers Tamara Chand made the highest purchase of $18437.14 while Alex Avila made the least purchase of $4,780.55. The year 2015 saw a total sales of $102,920.20 and a less significant drop in 2016 to $102,425.17 meanwhile a very significant increase of $145,673.88 was made in 2017 and dropping to $141,627.34 in 2018. The state with the highest sales is Texas $168,572.53 and the lowest is North Dakota with $919.19 sales. Top two products in this region are chairs $82,372.78 and Phones $71,939.95.

▪️The eastern region has a total sales of $669,518.73 between 2015–2018. The product categories sold in this region are technology making the highest sales of 39.30%, furniture 30.84% and office supplies 29.86%. Among the top ten customers Tom Asbrook made the highest purchase of $13,723.50 while Daniel Raglin made the lowest purchase of $6,937.87. There is a linear and progressive increase in sales trend from the year 2015 with total sales of $127,652.82, 2016 with sales of $153,225.18, year 2017 with total sales of $178,511.54 and 2018 saw the highest sales of $210,129.19. The state with the highest sales is New York with $306,361.15 and the lowest is West Virginia with of $1,209.82 sales. Top two products in this region are Phones $99,884.66 and chairs $95,687.51.

▪️The southern region recorded a total sales of $389,151.46 between 2015–2018. The product categories sold in the region are technology making the highest sales of 38.08%, office supplies 31.97% and furniture 29.95%. Among the top ten customers Sean Miller made the highest purchase of $23,669.20 while John Lee made the lowest purchase of $4,519.84. In the year 2015 the company recorded a total sales of $103,374.91, which decline to $70,076.08 in 2016 and progressively increased to $93,535.90 in 2017 and 2018 saw the highest sales of $122,164.57. The state with the highest sales is Florida with $88,436.53 and the lowest is West Virginia with of $8,481.71 sales. Top two products in this region are chairs Phones $58,098.34 and Machines $53,890.96.

▪️The western region has the highest sales with a total of $710,219.68 between 2015–2018. The product categories sold in this region are technology making the highest sales of 34.83%, furniture 34.55% and office supplies 30.62%. Among the top ten customers Raymond Buch made the highest purchase of $14,345.28 while William Brown made the lowest purchase of $5,523.05. The company recorded a total sales of $145,907.96 in 2015, declining to $133,709.57 in 2016 and progressively increased to $182,471.23 in 2017 and in 2018 the company recorded the highest sales of $248,130.93. The state with the highest recorded sales is California with $446,306.46 and the lowest is Wyoming with of $1,603.14 sales. Top two products in this region are chairs $100,023.20 and Phones $97,859.50.

# 8. Data Visualizations & Charts

 <img width="783" height="441" alt="image" src="https://github.com/user-attachments/assets/75b4011d-e2cc-4952-b489-47f4f89ebf77" />

The Pie-chart indicate that among the four regions analyzed, the Western region recorded the highest sales over the review period, totaling $710,219.68. This was followed by the Eastern region with $669,518.73 in sales. The Central region ranked third, generating $492,646.91. The Southern region reported the lowest sales performance, with a total of $389,151.46 during the same period.

 <img width="715" height="380" alt="image" src="https://github.com/user-attachments/assets/03fdc21d-a9db-4a38-883d-e37e160c0ffc" />

This chart shows that over the years, phones have consistently led in sales among all product sub-categories, generating a total of $327,782.45. Chairs follow closely with $322,822.73, while storage ranks third with $219,343.39. Tables and binders round out the top five, recording sales of $202,810.63 and $200,028.29 respectively.

 <img width="815" height="289" alt="image" src="https://github.com/user-attachments/assets/29c58b2f-0093-42a6-aea7-8569cd5e7df4" />

This line chart of yearly sales trend shows that 2018 recorded the highest sales, reaching $722,052.52. In contrast, the lowest sales was recorded in 2016, totaling $459,436.01. Sales in 2015 amounted to $479,856.21, while 2017 saw an increase, with total sales of $600,192.55.

 <img width="613" height="403" alt="image" src="https://github.com/user-attachments/assets/c59a5760-148e-4937-ac17-ec9595a86e25" />

This chart reveals the three product categories performance based on sales over the period reviewed where Technology leads with total sales of $827,455.87, followed by Furniture with $728,658.58, and Office Supplies closely behind at $705,422.33.

# 9. Post Analysis Recommendations

▪️Technology leads the product category across all regions for three consecutive years therefore implement more inventory on this category.

▪️A substantial amount of sales comes from California and New York therefore, consider expanding their warehousing capacity.

▪️The Central region shows balanced demand across all product categories, indicating market stability, however, prioritize Technology products in future shipments, as it has the highest share (34.25%).

▪️Conduct market research to identify barriers (e.g., low awareness, delivery issues) in States like North Dakota, West Virginia, and Wyoming which consistently show minimal sales and consider a targeted advertising or regional discounts to increase penetration.

▪️The steady year-over-year growth in the Eastern region presents a reliable market. therefore, maintain regular product updates and consider customer loyalty programs focused on top products like Phones and Chairs.

▪️After a dip in 2016, sales in the Southern region have shown a steady recovery, therefore, consider expanding inventory around furniture and Technology, which is showing potential growth.

▪️Ensure chairs, phones, and machines are consistently stocked and prioritized in procurement and logistics planning, particularly in high performing regions.

# 10. Conclusion

The analysis shows strong sales in the Western and Eastern regions, with technology and Furnitures leading across all markets. The Central region offers steady demand across categories, while the Southern region shows signs of growth. Targeted strategies by region and product type can help boost overall sales and support smarter distribution in the future.

# 11. References
kaggle.com

