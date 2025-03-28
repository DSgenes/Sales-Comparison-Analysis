# Sales-Comparison-Analysis

# Objective: 

    Conduct a comparison analysis of iPhone 15 sales and iPhone 14 sales. 

# Datasets: 

1. fact_sales_Iphone14.csv 
2. fact_sales_Iphone15.csv 
3. dim_stores.csv 

# Tasks: 

   Here is a brief overview of the workflow for the task: 

1. Review the data (fact_sales_Iphone14 and fact_sales_Iphone15).
 
2. Metrics to compare - iPhone 14 sales and iPhone 15 sales.
 
3. Calculate the variance (absolute difference value) between the iPhone 15 sales 
   and iPhone 14 sales for the identified metrics. ABS([Iphone 15 Sales]-[Iphone 14 Sales]).
   
4. Calculate the variance (in percentage) between the iPhone 15 sales and iPhone 
   14 sales for the identified metrics. [([Iphone 15 Sales]-[Iphone 14 Sales])/[Iphone 14 Sales].
    
5. Provide a complete report of the difference in numbers between the iPhone 15 
   sales and iPhone 14 sales data across the top 10 countries.

------------------------------------------------------------------------------------------------------------------------------------------

# Reviewing Data :

    You will be provided with three datasets for this analysis: 
    
1. dim_stores
2. fact_sales_iPhone14
3. fact_sales_iPhone15

------------------------------------------------------------------------------------------------------------------------------------------
# dim_stores: 

    This table contains all the information about stores
      
1. store_id: Unique identifier for each store.
2. country_name: Name of the country where the store is located.

-------------------------------------------------------------------------------------------------------------------------------------------

# fact_sales_IPhone14: 
       
    This table contains aggregated sales data for iPhone14 in September, October, and November of 2022.
        
1.	month: This column represents month and year in the format 'Mmm_yy'.
2.	store_id: Unique identifier for each store.
3.	iphone14: This column represents the actual sales data for a specific store in a given month for Iphone14.

-------------------------------------------------------------------------------------------------------------------------------------------

# fact_sales_IPhone15: 

   This table contains aggregated sales data for iPhone15 in September, October, and November of 2023.
      
1.	month: This column represents month and year in the format 'Mmm_yy'.
2.	store_id: Unique identifier for each store.
3.	iphone15: This column represents the actual sales data for a specific store in a given month for Iphone15.

------------------------------------------------------------------------------------------------------------------------------------------
# iPhone Sales Comparison Report

   This Power BI report analyzes and compares sales data for the iPhone 14 and iPhone 15 across the top 10 countries. The report includes:

         • Total Sales Comparison – iPhone 14 vs. iPhone 15
         
         • Absolute Variance – Difference in sales volume
         
         • Percentage Variance – Growth/decline rate
         
         • Visual Insights – Charts highlighting trends and country-wise performance

This project provides a data-driven approach to understanding sales trends and key market differences.

![image_alt](https://github.com/DSgenes/Sales-Comparison-Analysis/blob/69f01656fbae08067211c9e6ee82e3a334351687/Screenshot%20iphone.png)

# Key Insights : 

        • Growth Markets/Strong Growth: Brazil, Germany, and India show significant positive variance and an increase in iPhone 15 sales.
        
        • Declining Markets/Decline in Sales: UAE and the U.S. had a significant drop in sales and notable negative variance.
        
        • Overall Trend/Total Sales Comparison: iPhone 15 sales were -4.26% lower than iPhone 14 across these markets.

        • Positive % (e.g., Brazil: +19.69%) : iPhone 15 sales increased compared to iPhone 14.

        • Negative % (e.g., U.S.: -32.97%) : iPhone 15 sales dropped compared to iPhone 14.

        • Total Sales Variance: -4.26% : Indicates an overall slight decline in sales across the top 10 markets.

----------------------------------------------------------------------------------------------------------------------------------------------

