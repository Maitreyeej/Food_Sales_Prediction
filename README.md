This project is to showcase data science capabilities. It is a program which will give you the sales prediction of various food items. This is the very first project built after starting to learn data science.

This problem uses the data from https://s3.amazonaws.com/General_V88/boomyeah2015/codingdojo/curriculum/content/chapter/sales_predictions.csv

**This data has following columns:**

Item_Identifier\
Item_Fat_Content\
Item_Visibility\
Item_Weight\
Item_MRP\
Outlet_Identifier\
Outlet_Establishment_Year\
Outlet_Type\
Outlet_Location_Type\
Outlet_Size\
Item_Outlet_Sales

Goal is to predict the Item Sales in an outlet. This makes a column 'Item_Outlet_Sales' the target.

We will work with the given data and try to find the best fitted model to get the correct predictions and reduce the error. 

**Main Steps Involved:**

Step 1: Importing all the required modules.\
Step 2: Importing the data and creating pandas dataframe.\
Step 3: Checking the data basic information of the data like shape, datatypes and statistics.\
Step 4: Look for the missing and duplicate data.\
Step 5: Make analysis to decide how to deal with the missing data and get rid of the duplicated data if there is any.\
Step 6: Create some visualizations like histograms which would give a better idea about the data distribution.\
Step 7: Check for the correlation with the feature columns and plot the heat map to understand the extent of effect of features.\
Step 8: Deal with the categorical data as ML models require numerical data as input and get rid of the features which are not relevant.\
Step 9: Create the feature set and target column spit. And make the test train split of the data.\
Step 10: Build and fit various regression models to get the best fitting model.\
Step 11: Verify the models with the test data and evaluate the model based on the factors like R2 score, RSME etc.\
Step 12: Make the recommendations based on the findings.

***These visualisations give the idea of total sales as pet the fat content, type of outlets and outlet size.It will help us in giving the suggestions based on the analysis.***

![Unknown-10](https://user-images.githubusercontent.com/31748299/121499188-00289580-c992-11eb-8f5c-d52288bf1302.png)

![Unknown-11](https://user-images.githubusercontent.com/31748299/121500007-c1470f80-c992-11eb-9e2a-ee321046f808.png)

![Unknown-12](https://user-images.githubusercontent.com/31748299/121500437-23077980-c993-11eb-88c9-ea7acb138bad.png)


***These are the visualisations of the histograms for numerical data to understand the distribution.***

![Unknown-13](https://user-images.githubusercontent.com/31748299/121500615-534f1800-c993-11eb-9b11-e6b648ac9e19.png)



