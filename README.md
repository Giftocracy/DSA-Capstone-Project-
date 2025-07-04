# Project Topic: Product Review Analysis
My DSA project work on Amazon Product Review Analysis (Case Study 1)

### Project Overview
This project is aimed at Analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement

### Data Source
Open Dataset information scraped from Amazon product pages, including:
- Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data stored as comma-separated values

### Tools Used
Microsoft  Excel  download here (http://www.microsoft.com)

### Data Cleaning and Preparation
In the initial cleaning and preparation we performed the following actions:
- Data Loading and Inspection
- Data Handling missing variables

### QUESTION 1
Analysis Tasks
Use pivot tables and calculated columns where necessary to answer the following:
- What is the average discount percentage by product category?

ANSWER
- Downloaded the Amazon Case study dataset provided for the project
-	Went through the data set provided for project work and ensure proper data cleaning was done by expunging all unneeded data columns from the Excel sheet.
-	Made the columns headings bold and increased the font sizes
-	Inserted filters to the table columns headings
-	Selected any part of the data sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Category and drop in the Rows box
-	From the Field box, drag discount Percentage to Value box
-	Click on the arrow on the Value Box and click on Value Field Settings,  select Average from the box and on the Custom Name box , Rename the Columns heading (Average Discount Percentage) and click on OK.
-	Click on the Values under the Average Discount Percentage Columns and format to Numbers and click on the Homes Menu on the Excel menus and click on Decrease Decimal to 1 or 2 decimal places
-	Change the Row Heading on the Pivot Table to Category
-	Finally click on the top end of the Pivot Table and type the Name of the table (Average Discount Percentage by Product Category)
-	Final output is a sorted table showing the average discount percentage by product category
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 1 and press enter key on the keyboard

### QUESTION 2
How many products are listed under each category?

ANSWER
-	Selected any part of the data sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Category and drop in the Rows box
-	Drag product I.D and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings, select Count from the box and on the Custom Name box, Rename the Columns heading (Product Count) and click on OK.
-	Change the Row Heading on the Pivot Table to Category
-	Finally click on the top end of the Pivot Table and type the Name of the table (Number of ProductsUnder each Category)
-	Final output is a sorted table showing number of products under each category
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 2and press enter key on the keyboard

### QUESTION 3
What is the total number of reviews per category?

ANSWER
-	Selected any part of the data sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Category and drop in the Rows box
-	From the Field box, drag Rating Count to Value box
-	Click on the arrow on the Value Box and click on Value Field Settings, select Count from the box and on the Custom Name box, Rename the Columns heading (Total Reviews) and click on OK.
-	Change the Row Heading on the Pivot Table to Category
-	Finally click on the top end of the Pivot Table and type the Name of the table (Number ofReviews Per Products Category)
-	Final output is a sorted table showing total number of reviews per category
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 3 and press enter key on the keyboard to name the Worksheet

### QUESTION 4
Which products have the highest average ratings?

ANSWER
-	Selected any part of the data sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Product I.D and drop in the Rows box
-	From the Field box, drag Rating  to Value box
-	Click on the arrow on the Value Box and click on Value Field Settings, select Avearge from the box and on the Custom Name box, Rename the Columns heading (Highest Average Rating) and click on OK.
-	click on the value on the first cell on the Highest Average Rating column, press Control+Shift key on your keyboard+Down Arrow key to select all values on the column, click on Data Menu and select Sort Largest to Lowest 
-	This will show the highest rated product at the top
-	Final output is a sorted table showing products with the highest average ratings, helping you to identify top performing products
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 4 and press enter key on the keyboard to name the Worksheet


### QUESTION 5
What is the average actual price vs the discounted price by category?

ANSWER
-	Selected any part of the data set sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Category and drop in the Rows box
-	From the Field box, drag Actual Prize and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Average and click on ok
-	From the Field box, drag Discount Prize and drop in the Value box 
-	Click on the arrow on the Value Box and click on Value Field Settings and select Average and click on ok
-	Select all values on the Average Actual Prize Column and Average of Discounted Prize column by pressing Control+Shift key on your keyboard+Down Arrow key to select all values on both columns 
-	Right click and click on Format Cell and Select Number Option and select number of Decimal places and select ok
-	Final output is a table showing Category, Average Actual Prize and Average Discounted Prize. This helps you to compare pricing trends across different product category
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 5 and press enter key on the keyboard to name the Worksheet

### QUESTION 6
Which products have the highest number of reviews?

ANSWER
-	Selected any part of the data set sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Product I.D and drop in the Rows box
-	From the Field box, drag Rating Count and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Sum and on the Custom Name box, Rename the Columns heading of the values to Highest Review and click on OK.
-	Finally click on the top end of the Pivot Table and type the Name of the table (Productswith Highest Number of Reviews)
-	Final output is a sorted table showing number of products with the highest number of reviews
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 6 and press enter key on the keyboard
 
### QUESTION 7
How many products have a discount of 50% or more?

ANSWER
-	Create a new column on the data table with a heading titled Products with discount of 50% or more
-	Go to the column of the data table that has values of discount percentage, select all values provided on the column by holding down Shift+Control+Down arrow on your keyboard to select all values on the column
-	Press Control+C key on your keyboard to copy all the values, Paste all the values on the new column created by pressing Control+V keys on your keyboad
-	Select any part of the data table, click on Data Menu select Filter which inserts filters on all columns heading
-	Click on the drop down arrow of the new column created, select Numbers and select Greater than or equal to
-	In the Custom Auto Fill box first select Equal to, in the second box select 50%, in the third box select OR is Greater than, select 50% and click on ok
-	Final output is a sorted columns showing values of products with discounts of 50% and above
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 7and press enter key on the keyboard

### QUESTION 8
What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?

ANSWER
-	Selected any part of the data set sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Ratings and drop in the Rows box
-	From the Field box, drag Product ID and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Count and on the Custom Name box, Rename the Columns heading from Count of Product ID to Number of Products and click on OK.
-	Select your Row Label Heading and rename it to Rating
-	Final output is a table created showing  distribution of product ratings e.g 2.0, 2.3, e.t.c.
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 8and press enter key on the keyboard

### QUESTION 9
What is the total potential revenue (actual_price × rating_count) by category?

ANSWER
-	Create a new column on the data table with a heading titledPotential Revenue
-	Select the Cell under the columns heading, this Excel formular:  =D2*G2 and press enter key on your keyboard and the result will be the Potential Revenue
-	Right click on the value, select Format Cell, click on Currency, Select decimal places of your choice and press ok
-	Select the cell with the value, double click on the little black dot to the right and it automatically applies the same formula on all cells on the Potential Revenue column
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 9and press enter key on the keyboard
 
### QUESTION 10
What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?

ANSWER
-	Create a new column on the data table with a heading titledPrize Range
-	Select the Cell under the columns heading, type this Excel formular:  =IF(D2<200, "200", IF(D2<=500, "200-500", ">500")) and press enter key on your keyboard and the result will be the Prize Range
-	Select the cell with the value, double click on the little black dot to the right and it automatically applies the same formula on all cells on the Prize Range column 
-	Selected any part of the data set sheet and click on insert Menu and click on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag the New Prize Range and drop in the Rows box
-	From the Field box, drag Product ID and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Count and on the Custom Name box, Rename the Columns heading to Number of Products and click on OK.
-	Select your Row Label Heading and rename it to Prize Range
-	Final output is a table created showing Number of product per prize range

### QUESTION 11
How does the rating relate to the level of discount?

ANSWER
-	Create a new column on the data table with a heading titledHow Ratings Relate to Level of Discounts
-	Select the Cell under the columns heading, type this Excel formular: =CORREL(F2:F1466, E2:E1466) and press enter key on your keyboard
-	Select the cell with the value, double click on the little black dot to the right and it automatically applies the same formula on all cells on the column
-	Final output is a column created showing how Ratings relates to the level of Discount

### QUESTION 12
How many products have fewer than 1,000 reviews?
ANSWER
-	Create a new column on the data table with a heading titledNumber of Products with Less than 1000 Reviews
-	Go to the column of the data table that has values of Rating Count, select all values provided on the column by holding down Shift+Control+Down arrow on your keyboard to select all values on the column
-	Press Control+C key on your keyboard to copy all the values, Paste all the values on the new column created by pressing Control+V keys on your keyboad
-	Select any part of the data table, click on Data Menu select Filter which inserts filters on all columns heading
-	Click on the drop down arrow of the new column created, select Numbers and select Less than 
-	In the Custom Auto Fill box first select Less Than, in the second box select 1000  and click on ok
-	Final output is a sorted columns showing number of products with with less than 1000 reviews
-	Double click on the black dot on the buttom right of the cell pointer to automatically apply same formula to all values on the column

### QUESTION 13
Which categories have products with the highest discounts?

ANSWER
-	Selected any part of the data set sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Category and drop in the Rows box
-	From the Field box, drag Discount Percentage and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Max, on the Custom Name box, Rename the Columns heading to Products with Highest Discount and click on OK.
-	Select your Row Label Heading and rename it to Category
-	Final output is a table created showing  category of product with highest discounts
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 13 and press enter key on the keyboard

### QUESTION 14

Identify the top 5 products in terms of rating and number of reviews combined.

-	Selected any part of the data set sheet and clicked on insert Menu and clicked on Pivot Table
-	In the create Pivot Table dialog box, select Table or Rang and New Worksheet and click on Ok for the Pivot Table to be inserted on a new Worksheet.
-	From the Field box, drag Product ID and drop in the Rows box
-	From the Field box, drag Rating and drop in the Value box
-	Click on the arrow on the Value Box and click on Value Field Settings and select Max, on the Custom Name box, Rename the Columns heading to Top 5 Products by Rating and click on OK.
-	Select your Row Label Heading and rename it to Products
-	Final output is a table created showing Top 5 Productwith highest rating and reviews
-	Right Click on name tab of the workbook at the bottom of the Excel Sheet and rename it to Question 14and press enter key on the keyboard
