### MyLITA-Finals
## Project 1 Title: Sales Performance Analysis

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Explanatory Data Analysis](#explanatory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Inference](#inference)


## Project Overview
---
The aim of the data analysis is to explore sales data in order to uncover key insights; gathering enough information through the analysis of the various parameters in the data to tell captivating stories and knowing the best performance from the data.

## Data Sources
---
The primary source of Data used is the LITA Capstone Project .xslx

## Tools used
---
- Microsoft Excel [Download here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. For Visualization
- Structured Query Language for quering Data [Download here](https://www.microsoft.com/en-us/sql-server)
- Power Business Intelligence for visualization and connecting data across different dashboards [Download here](https://powerbi.microsoft.com)
- Github for portfolio building

## Data Cleaning and Preparation
---
At the beginning of Data Cleaning and Preparation, the following steps were taken.
 1. Data loading and Inspection
 2. The Data used is clean, there were Partial duplicates (OrderId) and were not removed.

## Explanatory Data Analysis 
---
This includes exploring of data to analyze top-selling products, regional performance, and monthly sales trends.

## Data Analysis
---
This includes some basic lines of queries

```SQL
SELECT 
    Product, 
    SUM(Revenue) AS TotalSales
FROM 
    SalesData
GROUP BY 
    Product;
```

## Data Visualization
---

![For Sales](https://github.com/user-attachments/assets/47bb6ede-5bc0-4239-b0a4-e27676bd72a6)

![SalesData Final](https://github.com/user-attachments/assets/6acb387c-8e08-478f-beb8-a95d69c59509)


## Inference 
---
1. Shoe is the highest product in demand coming from the South, followed by the East and lastly the West. The North has no record of any sales in shoes.
2. Hat and Gloves are in close rivalry.
3. The amount of the Averages Sales are proportional to the Quantity of Products sold.


## Recommendation
The North has no record of selling Shoes, so more attention should be focused there with plans of how to have a Shoe promotions there. It is evident that if the North is selling Shoes the Revenue will be very large, because despite the fact that the North does not have any record, Shoe is still the Product with the highest Revenue.

🙂


