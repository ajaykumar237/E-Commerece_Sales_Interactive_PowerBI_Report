# E-Commerce Sales Interactive Power BI Dashboard

### Project Overview
This project aims to provide insights into the sales performance of Amazon for the years 2012, 2013, 2014 and 2015. So that, Amazon can understand their customers and increase sales in the next years. 




![Store_Dashboard] 

### Data Sources
Sales Data: The primary dataset used for this analysis is the "Sales Data.xlsx" file, containing detailed information about each sale made by the Amazon.
### Tools
- Power BI - Data Cleaning, Data Calculation, Data Analysis and Dashboard Creation
  
### Data Cleaning/ Preparation
In the initial data preparation phase, performed the following tasks:
1. Data loading and inspection
2. Leveraged Power Query Editor for Extract, Tranform, Load (ETL)
   - Data Transform - made first row as headers in two sheets (Returns, People)
   - Data Extraction - made three new columns (Delivery Days, Year, Return 1)
  
     - Delivery Days = ([Ship date - Order date])
     - Year = Date.Year([order date])
       
   


### Data Analysis
1. Used pivot table to calcualte and analyse data
2. Created 6 pivot charts to visually analyse the data further
3. Connected all the charts with slicers for dynamic dashboard experience

### Results/ Findings

The analysis results are summarized as follows:
- Women are more likey to buy compared to men (~65%)
- Maharashtra, Karnataka, Uttar Pradesh are the top 3 buying states (~35%)
- Adult age group 30-49 years contributing max (~50%)
- Amazon, Flipkart and Myntra are max contributing (~80%)

### Recommendations
Based on the analysis, recommend the following actions:
  -  Target women customers of age group 30-49 years
  -  Aim for women who lives in Maharashtra, Karnataka, Uttar Pradesh
  -  Show ads/coupons/offers availabe on Amazon, Flipkart and Myntra

    
