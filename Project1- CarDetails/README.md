# CarDekho-Dashboard

### Dashboard Preview : https://github.com/user-attachments/assets/7c764e83-657d-4a32-9c31-8e052955282d


## Problem Statement

This dashboard helps the Customers understand market trends of cars and how drastically car industries are growing with new enhanced features, costs also increases based on different type of sellers, fuel type and Modes. It helps the car manufacturer know if their customers are satisfied with their services, they get to know their improvement area, as well as the scope to expand the customer requirement.It is easy for the customer to identify which seller is good to buy a car and what type of fuel cars are in demand in the market.

Since, 1995 Car business growing and it drastically increses in recent 4-5 years.
This Dashbord helps to showcse insights related to growing business.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors except few null values that has handled by removing from the table. 
- Step 5 : Added 2 Slicers added to get the data filter.
- Step 6 : Donut chart is used to find out the average selling price by seller type.
- Step 7 : Pie chart is used to find KM driven based on fuel type.
- Step 8 : 2 clusterd column charts has been added to find price per year and sells based on seller type. 
- Step 9 : A card visual is added to showcase average selling price of cars.

In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

# Snapshot of Dashboard

![dashboard_snapo](https://github.com/user-attachments/assets/7c764e83-657d-4a32-9c31-8e052955282d)


# Insights

A single page report was created on Power BI Desktop.

Following inferences can be drawn from the dashboard;

### [1] Slicers used to filter out Data
Based on car names or car release year one can filter the relevet information.

### [2] Card visual used to visualized overall sales
Average selling price of car

### [3] clusterd column charts
One of the clusterd column chart represent prices in billions per year since 1995, another one shows owner selles car based on seller type. 

### [4] Pie and Donut chart
Donut chart represent average selling price based on type of seller where as Pie chart represent Average KM Car Driven based on fuel type.

Refere PBIX file for actual Dashbord and CSV file attached. 
