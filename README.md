# Coffee Retail Chain - Sales Dashboard & Analysis  
- Description: Tableau dashboard and sales analysis storyboard for a coffee retail chain  
- Created: 6/10/23    
  
## Overview:  
- For this project, I created an imaginary retail chain called "The Bucks Coffee & Tea".  
- Acting as an analyst for The Bucks, I developed market and product performance dashboards for calendar years 2012 and 2013.  
- I then analyzed 2013 performance and created an executive summary as a Tableau storyboard.   

### Files & Links:  
- Data File: [Coffee.csv](Coffee.csv) from <a href="https://www.kaggle.com/datasets/arjunbhaybhang/coffee-chains-dataset?select=Coffee.csv" target="_blank">kaggle.com</a>
- Tableau File: 

### Development Approach:
- The data file from kaggle was already cleaned, so no additional cleaning steps were needed. 
- After loading the file into Tableau, I performed the following steps to transform the data as needed for the visuals:
    - Formatted the sales and budget columns as currency
    - Created a Date column to format the Excel date serial value into a date format
    - Created calculated fields for total sales per year, total sales year to date, sales year over year, sales by product type and for each product, and sales by market.
- I created several visuals to track key performance indicators for the company, and then combined them into two dashboards: a Market Performance Dashboard and a Product Performance Dashboard.  
- Using these dashboards, I conducted an analysis of 2013 performance.
- As a final step, I created a storyboard to highlight key insights gained from analyzing the visuals.
    
## Market Performance Dashboard:
- The Market Performance Dashboard can be filtered in various ways to allow users to gain insights into different aspects of performance.  
- Data can be viewed at the market or state level, by market size (major or small), and by year.  
- The following charts were used to visualize the data:  
    - Cumulative Sales by Market: Line Chart  
    - Profit by Market: Packed Bubble Chart
    - Marketing vs Sales by Area Code: Scatter Plot
    - Sales vs Budget: Combination Chart
    - Sales vs Expenses: Area Chart
  
|![Market Performance](images/market_dashboard.png)|
|-|

## Product Performance Dashboard:  
- The Product Performance Dashboard can be filtered in various ways to allow users to gain insights into different aspects of performance.
- Data can be viewed at the market level, by year, product type, product, and caffeine content.  
- The following types of charts were used to visualize the data:  
    - Profit by Product Type: Bar Chart
    - Sales by Product Type: Treemap Chart
    - Product Inventory: Lollipop Chart
    
|![Product Performance](images/product_dashboard.png)|  
|-|

## Executive Summary Storyboard:  
- The Executive Summary outlines key insights into market and product performance gained from analyzing the data. 
- The Storyboard tells the story of the company's performance by incorporating charts from the dashboards, with the following supplemental visuals:
    - Sales by Market and State: Dual Layer Map
    - Cumulative Sales Year over Year: Table
    - Profit by Product: Dot Plot

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_1.png?raw=true" name="story1">|  
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_2.png?raw=true" name="story2">|  
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_3.png?raw=true" name="story3">|  
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_4.png?raw=true" name="story4">|
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_5.png?raw=true" name="story5">|
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_6.png?raw=true" name="story6">|
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_7.png?raw=true" name="story7">|
|-|  

|<img src="https://github.com/mandi1120/coffee_retail_analysis/blob/main/images/story_page_8.png?raw=true" name="story8">|
|-|  
  
## Analysis & Data Story:
To develop an analysis of The Bucks' performance, I thought up some questions (goals for analysis) that would be important to better understand the health of the company. I then analyzed the visualizations to determine key insights (story points) in response to these questions.  
  
Goal #1:  Which market had the highest sales in 2013?  
Story:  
- The West Market was #1 in sales for 2013 at $139k.  
- The Central Market came in at #2 at $135k.  
- The South Market had the lowest sales for the year with $53k.  
  
Goal #2:  Which market had the highest profits in 2013?   
Story:   
- The Central Market earned the highest profits of $56k in 2013 despite being 2nd in overall sales.  
- The West Market came in 2nd for profits with $44k.  
- The South Market was last in profits at $19.  
  
Goal #3:  How did sales compare against budget for the company as a whole in 2013?  
Story:   
- Overall sales exceeded budgeted sales during every month of 2013.  
- During July when budgeted sales were highest at around $34k, actual sales also hit their highest point for the year at $36.  
- In October, budgeted sales were expected to drop to $29k, however actual sales held at $35k.  
  
Goal #4:  How did sales compare against expenses for the company as a whole in 2013?  
Story:  
- Overall sales exceeded expenses during every month of 2013.  
- Sales surpassed expenses by an average of $25k per month.
- Expenses were budgeted around $10k for each month of the year, while sales held around $35k with a slight drop in May and November.  
    
Goal #5:  Which products earned the most dollar sales in 2013?  
Story:  
- The Espresso category led in sales making up 27% of total sales for the year, followed closely by Coffee products at 26%.
- Colombian Coffee was the top selling individual product overall at $65k in sales.
- Lemon Herbal Tea was the #2 individual product at $49k in sales.  
  
Goal #6:  Which products earned the most profit in 2013?  
Story:   
- The Coffee product category earned the most profit in 2013 at $44k despite coming in #2 for total dollar sales.
- Colombian Coffee was #1 in profits for individual products, earning $33k for the year.
- Green Tea profits were slightly negative.  
   
Given additional time and resources for analysis, some additional insights that may impact overall conclusions are as follows:  
- What caused the higher dollar sales in the West Market? Is their pricing higher than other markets, or did they just sell more product?
- How many units of each product were sold?
- Do some products sell better during certain times of the year?
- What is the average customer rating for each store?




<br/>  
<br/>  
<br/>  
<br/>  
<br/>  
<br/>     
