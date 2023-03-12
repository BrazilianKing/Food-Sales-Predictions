![data science face](https://user-images.githubusercontent.com/123523010/224358015-f17e7602-e997-4785-af5f-f972a0435a5b.jpg)

# Food Sales Predictions

## Analyzing Food Sales Across Different Outlets Types 
Edmar Dos Santos

### Business are always trying to find a way to make the most ammount of money and spend the least. They also want to know which products are driving most of thier sales and which products are producing the highest ROI.

## Data: 
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view 

### For this dataset, there were 8523 rows and 12 columns.

# Methods
### To prepare this data, the data was cleaned, and the following processes were performed:
We sliced, flitered, searched for duplicates and dropped any coloumns that we felt were not import for this particual project.

# Visual 1 Title
![Item type vs MRP](https://user-images.githubusercontent.com/123523010/224516762-aae7f265-b85a-4413-a417-3c9f2fc678a9.png)

### Here in this data we are comparing the item types to the MRP to determine which item types requier more time and quantity of materials to complete a production process.

# Visual 2 Title
![outlet sales vs item MRP](https://user-images.githubusercontent.com/123523010/224517004-d8be19d7-70b0-4d92-b15d-fb833aa8d66e.png)

### Based upon this scatterplot it is very clear that there is a strong positive correlation between Item MRP and Item Outlet Sales. So the higher the MRP and item has the more sales that in generates in the outlets

# Results of Models
## The Decision Tree Model was chosen for this set of data
## Decision Tree Model Test Scores
### R^2(R-Squared Score): 0.162

### This score can be interpreted as saying that our model can account for about 16% of the variation in y_test using the features in X_test.

### RMSE(Root Mean Squared Error) : 1091.27

### This means the number is slightly higher because their were some test that had higher variance from the predictions. It impacts the total dollar amount because they are further away.
### These two metrics can help us predict new sales data within $1,100.

# Recommendations
### I would recommend checking the other models to see if we can find any improvments in our data.

# Next Steps
### I would say that more data needs to be include and to run more models with the new data being included.

# For futher questions: 
### Please email Edmar Dos Santos at edmardossantos85@gmail.com
