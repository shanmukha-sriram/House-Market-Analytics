 

"House-Market-Analytics-Dashboard"


Dashboard Link :  https://app.powerbi.com/links/YRhXMsfW-_?ctid=e7aa10ff-3a86-4274-a7f4-788b45a666bd&pbi_source=linkShare

Problem Statement:-

This dashboard helps analysts and real estate stakeholders understand housing market trends across different regions. It enables them to analyze property price movements, sales performance, and the relationship between offer prices and final purchase prices.

Through different analytical visuals, stakeholders can identify which regions are experiencing the highest price growth, which house types provide better yields, and how property characteristics influence market prices.

The dashboard also highlights the correlation between offer price and purchase price, allowing users to understand negotiation trends in the housing market.

Additionally, the Key Influencers analysis helps determine the most significant factors affecting house prices, such as property age, size (SQM), and house type.

Using these insights, investors, analysts, and decision-makers can make data-driven real estate investment decisions.

Steps followed

Step 1 : Load the housing dataset into Power BI Desktop. The dataset used for this project contains property sales information such as region, house type, price, size (SQM), and transaction details.

Step 2 : Open Power Query Editor and perform initial data exploration using the options under the Data Preview section such as:

Column distribution

Column quality

Column profile

Step 3 : Enable column profiling based on the entire dataset to analyze the full data rather than only the first 1000 rows.

Step 4 : Data cleaning was performed to remove inconsistencies, handle missing values, and ensure all columns had the correct data types.

Step 5 : A proper data model was created linking relevant tables and ensuring relationships between time, region, and property attributes.

Step 6 : In the report view, a theme and color palette were selected to maintain consistent dashboard design.

Step 7 : Multiple visuals were created to represent the housing market insights, including:

Bar charts

Scatter plots

Line charts

Donut charts

Cards

Key Influencers visual

Step 8 : KPI card visuals were added to highlight important metrics such as:

Units Sold (Latest Year & Quarter)

Last 12 Months Sales

Step 9 : A scatter plot was created to analyze the relationship between Offer Price and Purchase Price, helping identify pricing patterns in the market.

Step 10 : A bar chart was used to display Median Sales Price Change by Region, allowing easy comparison across regions such as:

Jutland

Zealand

Bornholm

Fyn & Islands

Step 11 : A YOY Sales Growth visual was created to analyze how different sales types (auction, regular sale, family sale, other sale) are performing year-over-year.

Step 12 : A Sales by Region visual was added to identify which regions contribute the most to overall housing sales.

Step 13 : The Key Influencers visual was used to determine factors influencing purchase price.
The analysis revealed that property age greater than 77 years significantly increases the average purchase price.

Step 14 : Additional analysis was performed on house types, including:

Farm

Villa

Apartment

Townhouse

Summerhouse

Step 15 : Visuals were created to compare Average Offer Price vs Purchase Price by House Type.

Step 16 : Another visual was developed to analyze Inflation, Interest, and Yield trends across different house types.

Step 17 : A combined bar and line chart was created to analyze Average SQM and SQM Price by House Type.

Step 18 : The final dashboard was then published to Power BI Service for sharing and visualization.

Snapshot of Dashboard (Power BI Service)

 <img width="1902" height="1058" alt="Image" src="https://github.com/user-attachments/assets/a68d0dad-adeb-4dd2-a705-6eabf5f3e9ce" />

Report Snapshot (Power BI Desktop)

 <img width="1624" height="923" alt="Image" src="https://github.com/user-attachments/assets/6e2852cf-7ea3-4312-bc56-5a736d572894" />
<img width="1643" height="926" alt="Image" src="https://github.com/user-attachments/assets/8732eae0-ff57-4cf0-adc6-279fdabfff76" />

<img width="1631" height="898" alt="Image" src="https://github.com/user-attachments/assets/1ac3d552-0237-4269-97ee-a86980a98040" />

Insights

A multi-page report was created in Power BI Desktop to analyze housing market performance across regions and property types.

Following insights can be drawn from the dashboard:

[1] Regional Sales Performance

Zealand recorded the highest housing sales with approximately 95bn in total sales.

Jutland followed with around 81bn in sales.

Fyn & Islands recorded about 15bn in total sales.

Bornholm had the lowest sales with approximately 1bn.

This indicates that Zealand is the most active real estate market among the analyzed regions.

[2] Median Sales Price Change by Region

Jutland experienced the highest positive median price growth.

Fyn & Islands and Zealand also showed moderate growth.

Bornholm experienced a slight decline in median sales price.

[3] Offer Price vs Purchase Price Trend

The scatter plot indicates a strong positive correlation between offer price and purchase price, meaning properties are generally sold close to their listed offer price.

However, a few outliers show significant differences between the two values, indicating negotiation or special transaction conditions.

[4] Key Influencing Factors for Purchase Price

Using the Key Influencers AI visual, it was identified that:

Properties older than 77 years increase the average purchase price significantly.

This insight suggests that historical or older properties may carry higher value due to location or architectural significance.

[5] House Type Price Comparison

Average purchase prices across different house types:

Farm properties have the highest average price (~2.7M).

Apartments average around 2.4M.

Townhouses average around 2.1M.

Villas average around 1.8M.

Summerhouses have the lowest average price (~1.2M).

[6] Yield Analysis by House Type

Farm properties provide the highest yield (~4.6).

Villas provide around 4.2 yield.

Apartments and townhouses provide moderate yields (~3.9).

Summerhouses have slightly lower yields (~3.8).

[7] Property Size and Price Analysis

Farms have the largest average property size (~196 SQM).

Villas average around 152 SQM.

Townhouses average around 108 SQM.

Apartments average around 86 SQM.

However, apartments tend to have the highest price per SQM, indicating strong demand in urban areas.

✅ This project demonstrates the use of Power BI for real estate analytics, combining data modeling, DAX calculations, AI insights, and interactive visualizations to transform raw housing data into meaningful business insights.
