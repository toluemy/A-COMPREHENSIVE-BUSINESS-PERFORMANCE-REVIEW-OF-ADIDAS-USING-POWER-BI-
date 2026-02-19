A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-

 In this analysis, we worked with Adidas sales dataset to understand how the brand is performing across different regions, retailers, products and time periods. The goal was to go beyond just number and uncover the meaningful patterns in customer buying behavior, product demand and overall sales performance.

# Dataset used
https://github.com/toluemy/A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-/blob/main/Adidas%20US%20Sales%20Datasets11.xlsx

# Problem Statement
Adidas operates in a highly competitive and dynamic market. Fluctuations in sales performance, regional demand differences, product category and consumer preferences can significantly impact overall profitability and growth. The challenge is to analyze Adidas sales and performance data to identify key trends, revenue drivers and growth opportunities.

## Objectives

1.To analyze how different sales method impact overall sales performance. 

2.To identify the products the consumers prefer the most.

3.To identify the regions that generate the highest profits.

4.To identify the retailers with the highest profit.

5.To examine the quarterly sales trend .

<img width="1184" height="502" alt="addidas" src="https://github.com/user-attachments/assets/41fd99e7-0b79-42da-961e-aabe9396b6b7" />


# DATA SOURCE & DATA CLEANING PROCESS
The Adidas dataset was gotten from Kaggle.com. The dataset contains 9648 rows and 11 columns. We  checked for duplicates but there were no duplicates. We  also checked for blank cells but there were no blank cells. In the process of transforming the dataset we created three calculated columns to help us with the analysis. The title of the columns are:
	Total Revenue = Price per Unit Column multiplied by Unit Sold Column
	Total Cost = Cost per Unit Column multiplied by Unit Sold Column 
	Profit = Subtraction of Total Cost Column  from  Total Revenue Column
So in total the dataset has 14 columns and 9648 rows.

# ANALYTICAL QUESTIONS
Below are the analytical questions:

1. How do sales methods (Online, Outlet and In-Store) influence the profit?
2. Which product category contributed most to Adidas’ profit?
3. Which region generated the highest profit for Adidas?
4. Which retailer contributed the most to the overall profit?
5. What was the quarterly sales trend?

![image Alt](https://github.com/toluemy/A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-/blob/ba0e9ca726ad28f971799dd8c7267be1c89b2bbd/sales%20method.png)

## ANALYSIS

The Total Profit by Sales Method chart reveals that the Online sales generated the highest profit ($19.55M) followed by Outlet sales ($14.91M), and In-store sales ($12.76M).This indicates that Adidas performs strongly across all channels, but online is clearly the leading sales method.

INSIGHTS: Online sales being the top contributor suggests:
Strong digital presence
More customers prefer online shopping

![image Alt](https://github.com/toluemy/A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-/blob/b98a655d716402bfd930365b808d83aefccfd1d9/profitproduct.png)

## ANALYSIS

The Total Profit by Product chart shows that Men’s Street Footwear generates the highest profit among all products, followed closely by Women’s Apparel and Men’s Athletic Footwear.On the lower end, Women’s Athletic Footwear and Men’s Apparel generate the least profit in comparison to the top products.

INSIGHT
Men’s Street Footwear is the strongest-performing category, indicating high demand for men’s shoes.Women’s product categories show mixed performance: women’s apparel performs strongly, while women’s athletic footwear underperform

![image Alt](https://github.com/toluemy/A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-/blob/b4a5606bbb63e264e33d54b5eb0e5760328b0972/proregion.png)

# ANALYSIS
The Total Profit by Region Chart across five regions.
1. West Region is the strongest performer, it produces the most profit, suggesting strong market demand.
2. Northeast, Southeast, and South shows moderate profit levels with profits that follow a similar pattern. 
3. Midwest shows the lowest profit.

![image Alt](https://github.com/toluemy/A-COMPREHENSIVE-BUSINESS-PERFORMANCE-REVIEW-OF-ADIDAS-USING-POWER-BI-/blob/fc1dfafaa2bea96e694bf4a07f19e40d7db515d8/proretailer.png)

# ANALYSIS

The Total Profit by Retailer Chart reveals that;
1.  West Gear is the top-performing retailer that generated the highest profit by a clear margin.
2. Foot Locker and Sports Direct follow closely forming a strong top-three profit group.
3. There is a sharp drop in profit after Sports Direct.
4. Kohl’s and Amazon contributed significantly less profit with Walmart being the lowest among the group.





















