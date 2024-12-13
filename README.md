# Ecommerce Sales-Dashboard


## Problem Statement

An e-commerce business often faces challenges in analyzing its sales, profits, and orders, identifying the states and customers with the most traffic and orders placed, and accordingly performing customer relationship and marketing campaigns to improve the profit figure more and have a deeper analysis of the profits quarter-wise.
This dashboard focuses on and analyzes all the aspects of the ecommerce platform to generate useful insights that help in making better business decisions by the stakeholders. 



### Steps followed 

- Step 1 : The data was present in 2 datasets, one being the orders data and the other being the details data, both were loaded in power bi.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : While checking for the errors it was found that the data was clean data so no cleaning operation was performed.
- Step 5 : To check the relationship between both the datasets, click on model view where the relationship between this two datas was many to one and the mapping was done on the order id column.
- Step 6 : The background theme was not designed using Power Bi but was uploaded from other sources.
- Step 7 : Two slicers used in this project, one for the purpose of viewing the dashboard in the different quarters of the year and the other to filter the results on the basis of the states. 
- Step 8 : Four card visuals are used to display the Sum of Amount, Sum of Profit, Sum of Quantity, Sum of Average Value of Orders(AOV).
- Step 9 : As the Average value of order this column was not present in the dataset so an extra measure was created for it.
For creating this new column the following DAX expression was used:-

AOV = (details[Amount])/(details[Quantity])

- Step 10 : Two stacked column chart is used to represent Profit by month and the other one for the sum of amount by the cutomer.
The first column chart is used to analyze the state from where the ecommerce platform is generating the most profits and the other column chart is used to identify the customers who have ordered the most from the store.
- Step 11 : Two donut visuals are used both represent sum of quantity, one by category and the other by the payment mode.

- Step 12 : In the report view, under the insert tab, two text boxes were added to the canvas, in one of them name of the airlines was mentioned & in the other one company's tagline was written.
- Step 13 : Two clustered bar chart visuals are used to sum of profit by sub-category and the other shows sum of amount by state.
- Step 14 : in the report view, the text box is used to write the company name and the title to the dashboard.
 
 # Report Snapshot (Power BI DESKTOP)

 
![ecommerce db](https://github.com/user-attachments/assets/ff9c570a-9fb3-433d-ad3f-75597ea7e80e)


# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1]  For whole calander year:
	Overall Profit in the calendar year was -37k
	Overall average order value was - 121k
	Total quantity of orders sold was - 5615
	Sum of amount earned this year - 438k
	Looking upon the maximum profit earned was 10253 in the month of November
	Maharashtra state stands highest on the table with 102498 amount earned 
	Category wise Clothing was the most sold category with 63% of the orders followed by        electronics and furniture
	It is observed that the most favourable way of payment by the customers was Cash on delivery followed by UPI,Debit card and then credit card.
	The loss making months in the whole year was may, july, september,december.	
	
### [2] First Quarter
    Overall Profit in the first quarter was -26k
	Overall average order value was - 44k
	Total quantity of orders sold was - 2008
	Sum of amount earned in the first quarter - 161k
	Looking upon the maximum profit earned was 9684 in the month of January
	Maharashtra state stands highest on the table with 32207 amount earned 
	Category wise Clothing was the most sold category with 63% of the orders followed by        electronics and furniture
	It is observed that the most favourable way of payment by the customers was Cash on delivery followed by UPI,Debit card ,EMI and then credit card.
	No Loss incured in the first quarter.
  
  ### [3] Second Quarter
  
    Overall Profit in the second quarter was -882
	Overall average order value was - 24k
	Total quantity of orders sold was - 1181
	Sum of amount earned second quarter - 87k
	Looking upon the maximum profit earned was 4192 in the month of April
	Maharashtra state stands highest on the table with 21319 amount earned 
	Category wise Clothing was the most sold category with 61% of the orders followed by        electronics and furniture
	It is observed that the most favourable way of payment by the customers was Cash on delivery followed by UPI,Debit card ,credit card and then EMI.
	May Month suffered loss of 3730 in the second quarter.


 ### [4] Third Quarter
 
 	Overall Loss in the third quarter was - 1469
	Overall average order value was - 19k
	Total quantity of orders sold was - 1017
	Sum of amount earned third quarter - 72k
	Looking upon the maximum profit earned was 2068 in the month of Augustl
	Madhya Pradesh state stands highest on the table with 22659 amount earned 
	Category wise Clothing was the most sold category with 60% of the orders followed by        furniture and electronics.
	It is observed that the most favourable way of payment by the customers was Cash on delivery followed by UPI,credit card ,debit card and then EMI.
	July Month suffered the most loss of 2138 in the third quarter.


 ### [4] Fourth Quarter
 
 	Overall Profit in the fourth quarter was - 12k
	Overall average order value was - 33k
	Total quantity of orders sold was - 1409
	Sum of amount earned fourth quarter -118k
	Looking upon the maximum profit earned was 10253 in the month of November
	Maharashtra state stands highest on the table with 31431 amount earned 
	Category wise Clothing was the most sold category with 66% of the orders followed by        electronics and furniture.
	It is observed that the most favourable way of payment by the customers was Cash on delivery followed by UPI,credit card ,EMI and then debit card.
	December Month suffered the most loss of 1604 in the fourth quarter.

