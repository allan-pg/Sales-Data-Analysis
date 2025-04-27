# Sales Data Analysis in Excel
![image](https://github.com/user-attachments/assets/94732224-3d69-4efb-9f8b-3354f6efb0a4)

## About the data
Mock data is sales data made throught the year of 2021 by a company. Its made of 8 rows and 1000 rows. You can download Mock_data.csv from this repo 
The columns are:-  
1. Sales Information  
- sales_person id  
- sales value   
- sales date  
- sales reion  
- sales quantity  
2. customer information  
- customer name  
- customer email  
- customer country  

## Objectives  
- Identify sales trend throughout the year
- Calculate and Identify sales by Channel
- Identify sales by region
- Identify sales made by different sales person

## Tools Used
- Excel Power Query
- Pivot Tables
- Excel Tables
- Excel Pivot charts

## Data Transformation
### 1. Transformed and Standardized sales_date column  
The sales date column was stored as a text, which was changed to correct date type using power query  

**In Power Query editor:-**  
- Select sales_date column  
- Click on Data Type dropdown > chose "Using Locale..."  
- Select:-  
Data Type: Date  
Locale: English(united states) mm/dd/yyyy    

### 2. Tranformed Sales_Amount column to Currency
Changed sales_value to Currency from Text

### 3. Tranformed Sales_Quantity column to int
Changed sales_quantity to int from Text  

- **Results:**  
Dates were correctly recognized and standardized across dataset    
Sales_Amount Sales_Quantity and were transformed to correct data types  



## FINDINGS
### 1. Total sales
- $5,038,142 were total sales made overall
### 2. Trend Alert:
- sales has been on a decrease from 492656 in august to 316944, which is a 39.56 decrease in sales
3. Top Region by Sales Amount
- In North America of we made the highest sales of $1,080,783 while in Africa we made least sales of $939,968 
### 4. Top Sales Channel
- Direct Sales made the highest sales of $ 1,304,220 while in Distributor Channel we made least sales of $1,167,704
### 5. Sales Person Performance
- Several Sales persons like ID 231 have sales between $9,965 - $9,995 in sales, indicating relatively even performance among top salespeople
### 6. Top Region by products sold
- South America had highest number of products sold

## Reccomendations
### 1. Adrress the Sales Decline
- Investigate why there is a decline in sales in the last Quarter which can be due to:-  
Seasonality  
Competition  
Customer Churn  

- Plan targeted campaign in Q4 to address the dip
### 2. Invest more on High Performing Channels
- consider investing more customer outreach on Direct Sales, best channel 

Boost Other Channels:-
- Try to improve Distributor and In line Channels through better promotions to reduce dependence on Direct Sales

### 3. Capitalize on South America
- Products are selling well in South America - Expand Product range to maximize on revenue

### 4. Reward and retain Top Sales Persons
- Top Salespeople are very close in performance - launch sales reward to keep them motivated

### 6. Expand Data Tracking
- In future versions include customer acquisition cost, repeat customer rates for more deeper insights.
