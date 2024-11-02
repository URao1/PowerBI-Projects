# Call Center Analysis-Dashboard

## Problem Statement

This dashboard helps to understand market trends of call center,how many agents are register to call center and how many issues are resolved and answered, customer satisfaction based on the issue resolution. It also gives glipms of agents statistics shows satisfaction rate and the agent speed to answer and resolve the issues.

The dataset is taken for PWC company.

Call center supports topic related to Admin,Contract related,Payment related,Streaming and Technical support. Slicers provided for better visibility.

### Dashboard Preview : 
![dashboard_snapo](https://github.com/user-attachments/assets/036442f6-b50a-4392-a2d3-74b845802b4e)

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : It was observed that in none of the columns errors except few null values that has handled by removing from the table. 
- Step 4 : Added 3 Slicers added to get the data filter.
- Step 5 : Donut chart is used for answered and not answered percentage.
- Step 6 : Pie chart is used for resolved and unresolved percentage.
- Step 7 : A stacked column charts has been added to find answered issues per month.
- Step 8 : A card visual is added to showcase average selling price of cars.
- Step 9 : Gangue chart represents the ratings
- Step 10 : Matrix chart added to show detailed work for each agent.


# Insights

A single page report was created on Power BI Desktop.

Following inferences can be drawn from the dashboard;

### [1] Slicers used to filter out Data
Three Slicers are used where data can be filter based on agent names ,topic for calling ,date.

![dashboard_snapo](https://github.com/user-attachments/assets/765766b1-12ce-4570-8a88-dd545b35f918)

### [2] Card visual shows average speed of answers
![dashboard_snapo](https://github.com/user-attachments/assets/a89290fb-b764-45c8-80d9-500d5324f940)

### [3] Stacked column chart
Column chart displays number of calls answered out of total number of calls. Since data contain 3 months only hence it represent for those 3 months.

![dashboard_snapo](https://github.com/user-attachments/assets/d527c038-c559-43d0-9215-77731bd3640c)

### [4] Pie and Donut chart
Donut chart represents percentage of answered calls and Pie chart represents percentage of resolved issues from answered calls.

![dashboard_snapo](https://github.com/user-attachments/assets/4e855622-28b2-435e-af73-e80d3ed50cc2)

### [5] Ratings 
Gangue chart used to show the average satisfaction of the customer.

![dashboard_snapo](https://github.com/user-attachments/assets/be7c1f48-1f60-4484-ad43-d5b967bcb0d4)
