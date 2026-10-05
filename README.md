# EASYSHOPPING-Sales-Performance-and-Profitability-Analysis
Sales performance and profitability analysis of EasyShopping using Microsoft Excel.

<img width="1050" height="381" alt="image" src="https://github.com/user-attachments/assets/d9767934-c268-49e7-9f10-4d87080647de" />


* PROJECT OVERVIEW

This project analyzes EasyShopping's sales data to understand how the business performed during the period under review. The work moved from raw transaction data through cleaning and calculated fields to PivotTable analysis, visualizations, and a final interactive dashboard. The goal was not only to report numbers, but to use them to identify areas that can support better business decisions.

* BUSINESS PROBLEM

EasyShopping needed a clear view of its sales and profitability performance across products, cities, months, and sales channels. The analysis was carried out to identify the main revenue and profit drivers, compare performance across different areas of the business, and highlight opportunities for improving sales and profitability.

* BUSINESS QUESTIONS

•	What are the total revenue, profit, COGS, profit margin, and number of transactions?

•	Which products contribute the most revenue and profit?

•	Which cities contribute the most revenue?

•	How does revenue change from month to month?

•	Which sales channel contributes the most revenue?

•	Are the strongest revenue drivers also strong from a profitability perspective?

•	What practical actions can EasyShopping take based on the results?

* DATASET OVERVIEW

The dataset contains 120 cleaned transactions covering customer orders, dates, locations, products, quantities, prices, costs, discounts, sales channels, and payment methods. The original fields included Order ID, Order Date, Customer Name, City, Product, Quantity, Unit Price, Unit Cost, Discount, Sales Channel, and Payment Method.

<img width="945" height="550" alt="image" src="https://github.com/user-attachments/assets/0c26f35d-3b5e-4670-8ad9-7a5e4cf5fb4f" />

* DATA CLEANING AND PREPARATION

Before analysis, the data was reviewed for duplicates, missing values, inconsistent text, and date-format issues. Corrections were made only after checking the surrounding records and the business logic of the fields.

<img width="990" height="383" alt="image" src="https://github.com/user-attachments/assets/7ccaf797-9ff3-4708-8776-b4779e4d5c70" />


* DATA TRANSFORMATION AND CALCULATED FIELD

After cleaning, additional fields were created to make the dataset ready for analysis. These calculations helped convert the raw transaction fields into business measures that could be summarized in PivotTables.

Calculated field	      Logic	                  Purpose

Gross Sales	          Quantity × Unit Price	      Value before discount

Discount Amount	      Gross Sales × Discount	    Value of discount given

Total Sales/Revenue	  Gross Sales − Discount      Revenue after discount

Total Cost/COGS	      Quantity × Unit Cost	      Cost of goods sold

Profit	              Revenue − COGS	            Amount earned after product cost

Profit Margin	        Profit ÷ Revenue	          Profitability as a percentage

Month	                Extracted from Order Date	  Monthly trend analysis

Weekday	              Extracted from Order Date	  Day-of-week analysis

<img width="1030" height="306" alt="image" src="https://github.com/user-attachments/assets/1181b494-1a2c-4a04-ad97-1567a0bb390a" />
                                          Date, month, weekday and sales calculations
                                          
<img width="990" height="470" alt="image" src="https://github.com/user-attachments/assets/ad9a29b8-b010-4668-b681-07fdeda7773d" />
                                          Revenue, COGS, profit and profit-margin calculations
                                          
* PIVOTTABLE ANALYSIS

PivotTables were used to summarize the cleaned data and compare performance across products, cities, months, and sales channels. The summaries provided the basis for the charts and dashboard.

<img width="1050" height="348" alt="image" src="https://github.com/user-attachments/assets/e69f5b8e-1211-4661-949d-bd59f9e0ca32" />
                                            PivotTable summaries used for the dashboard
* KEY PERFORMANCE INDICATOR

  KPI	                  Result
Revenue                	₦3,079,935
COGS	                  ₦2,645,400
Profit	                ₦434,535
Profit Margin	          14.11% (displayed as 14% on dashboard)
Transactions	          120

The business generated ₦3.08 million in revenue from 120 transactions and recorded ₦434,535 in profit after COGS. This gives an overall profit margin of about 14.11%. In simple terms, the business retained roughly ₦14.11 in profit for every ₦100 of revenue before other operating expenses not included in this dataset.

* PRODUCT PERFORNAMCE
  
<img width="870" height="526" alt="image" src="https://github.com/user-attachments/assets/19bd6d35-6c9b-40a0-8de0-e91775305baf" />

Beans 5kg generated the highest revenue at ₦1,120,950, followed by Rice 5kg at ₦686,800 and Cooking Oil 2L at ₦452,250. Beans 5kg also generated ₦132,950 in profit. Rice 5kg generated a lower revenue than Beans 5kg but recorded the highest profit in the product summary at ₦161,675.

* CITY PERFORMANCE

<img width="870" height="500" alt="image" src="https://github.com/user-attachments/assets/8af7e3cf-3779-48ba-9573-927ca2dd3843" />

Lagos was the strongest revenue-generating city, contributing ₦1,469,485, followed by Ibadan at ₦718,780. Abuja and Port Harcourt contributed ₦447,850 and ₦443,820 respectively.
Lagos is therefore the most important market in the current dataset by revenue. It would be useful for stakeholders to understand what is driving this performance and whether the same pattern is seen in profit and order volume before increasing investment in the market.

* MONTHLY PERFORMANCE

<img width="930" height="354" alt="image" src="https://github.com/user-attachments/assets/49a511df-2e63-4813-8ae3-04d3c4443d90" />

January recorded the highest monthly revenue at ₦594,415. March followed with ₦555,750, while May recorded the lowest revenue at ₦449,900. The monthly figures show a decline from January through May, with June recovering slightly to ₦500,940.

* SALES CHANNEL PERFORMANCE

<img width="870" height="509" alt="image" src="https://github.com/user-attachments/assets/e7ed4ff6-64e2-47dd-887e-6e4d1152dc40" />

WhatsApp was the leading sales channel, accounting for 47% of revenue. Phone calls contributed 22%, Instagram 16%, and Walk-in sales 14%.
WhatsApp is therefore the strongest revenue channel in this dataset.

* FINAL DASHBOARD

<img width="1050" height="371" alt="image" src="https://github.com/user-attachments/assets/d0c910e7-63ca-44a9-b8cc-253d76a01489" />

The dashboard brings the analysis together in one view. KPI cards summarize revenue, profit margin, COGS, and transactions, while charts show performance by product, city, month, and sales channel. City and month slicers allow the user to filter the dashboard and explore the results interactively.

* KEY FINDINGS

•	EasyShopping generated ₦3,079,935 in revenue and ₦434,535 in profit from 120 transactions.

•	The overall profit margin was approximately 14.11%.

•	Beans 5kg was the highest-revenue product, while Rice 5kg recorded the highest product-level profit in the summary.

•	Lagos was the strongest revenue-generating city, contributing about ₦1.47 million.

•	January recorded the highest monthly revenue, while May recorded the lowest.

•	WhatsApp was the strongest sales channel, accounting for 47% of revenue.

* BUSINESS RECOMMENDATIONS

Promote and develop underperforming products: EasyShopping should continue to prioritize its profitable and high-performing products while strategically promoting products with lower sales. This can be achieved by increasing customer awareness, highlighting the benefits and usefulness of these products, and communicating how they can meet customers’ specific needs.

Strengthen the WhatsApp channel: Since WhatsApp generated the largest share of revenue, the business can continue investing in customer engagement and promotions through the channel.

Build on the Lagos market: Lagos is the strongest revenue market in the dataset. Management can study what is working there and apply successful approaches to weaker markets.

Investigate monthly demand: The difference between January and the weaker months should be investigated so that successful campaigns, customer behavior, or product availability can be repeated.

Monitor profitability: Revenue growth should be tracked together with COGS, profit, and profit margin so that higher sales do not come at the expense of profitability.

* CONCLUSION

This project turned raw EasyShopping transaction data into a usable business intelligence report. The process covered data cleaning, transformation, PivotTable analysis, visualization, and dashboard development. The results show a business with ₦3.08 million in revenue, ₦434,535 in profit, and a 14.11% overall profit margin, with clear differences across products, cities, months, and sales channels. The analysis provides a practical starting point for making better decisions around product focus, marketing channels, market expansion, and profitability.

* TOOLS AND SKILLS DEMOSTRATED

•	Microsoft Excel

•	Data cleaning and quality checks

•	Data standardization and date formatting

•	Calculated columns and business metrics

•	PivotTables and slicers

•	Data visualization and dashboard design

•	Business-question formulation

•	Insight generation and business recommendations

