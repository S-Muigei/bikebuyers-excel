# bikebuyers-excel - Cleaning and Analyzing using pivot charts and interactive dashboards in excel

#Created a new worksheet
#Cleaned the data by removing duplicates. Did this by selecting ID, then going to Data and clicking next to the ‘Text to Columns’ command which is the remove duplicates command.
   
#Find and replace some data fields to be clearer. Select the ‘Marital status’ column then CTRL + H, (Find & Replace command) then replace M with Married and S with Single. Search by columns.

#Remove decimals in numbers and make them whole numbers.

#Group ‘ages’ to ‘age groups’ to have more precise and summarized data. 

#Add a new column and call it ‘Age groups’ then use the IF statements to classify each age group. For example, IF(L2<20,"TEENAGER")

Start creating pivot tables. Go to Insert, then select pivot tables and go to the working sheet. Select the whole table.

To determine the income averages for gender and purchasing a bike, select ‘Gender’ as the Axis, average income as the values, and Gender as the legends.
NB: To change from sum to average, click on the sum and change to average.

Create more pivot tables to check for commuter distance and purchasing a bike correlation and gender brackets for bikes purchased.

Create visualization for each of these pivot tables by inserting the chart and selecting appropriate charts for each that adequately summarize the table.
NB: Add legends, chart titles, and axes names by going to chart design. 

Create a new sheet for the interactive dashboard. Copy all the charts to this new worksheet and then select chart and go to pivot chart analyze
; 
12.	Enter ‘insert slicer’ and select the field you'd like to compare. Eg cars, then go report connections to make sure this will be filtered across all charts. 
13.	11.  Draw conclusions from all the different filters. E.g, People who purchase more bikes across all ages are likely to be middle-aged men.

![image](https://github.com/S-Muigei/bikebuyers-excel/assets/141069085/ebd0b399-a520-4b8d-ac26-e70c3e3d10a3)
