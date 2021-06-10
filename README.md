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
Step 11: Verify the models with the test data and evaluate the model based on the factors like R2 score, RMSE etc.\
Step 12: Make the recommendations based on the findings.

***These visualisations give the idea of total sales as pet the fat content, type of outlets and outlet size.It will help us in giving the suggestions based on the analysis.***

![Unknown-10](https://user-images.githubusercontent.com/31748299/121499188-00289580-c992-11eb-8f5c-d52288bf1302.png)

![Unknown-11](https://user-images.githubusercontent.com/31748299/121500007-c1470f80-c992-11eb-9e2a-ee321046f808.png)

![Unknown-12](https://user-images.githubusercontent.com/31748299/121500437-23077980-c993-11eb-88c9-ea7acb138bad.png)


***These are the visualisations of the histograms for numerical data to understand the distribution. Outlet Establishment year shows that there were not a lot of outlet established in some years.***

![Unknown-13](https://user-images.githubusercontent.com/31748299/121500615-534f1800-c993-11eb-9b11-e6b648ac9e19.png)


***This visulaisation gives the idea of the number of outlets established in the year.***

![Unknown-15](https://user-images.githubusercontent.com/31748299/121502013-9b226f00-c994-11eb-859f-05ef44e22c17.png)


***This visualisation gives the idea on the correlation between the fetures in the data. Based on this we can decide if some columns can dropped.***

![Unknown-14](https://user-images.githubusercontent.com/31748299/121501235-e5efb700-c993-11eb-8be2-68e0f10d8744.png)


After we looked through the visualisations, we split the data into testing and training data.

We tested by fitting various models of regression to the data and evaluated all the models to get the best fitted model out of these.

Models tested:
1. Linear Regression\
2. Nearest Neighbor\
3. Random Forest\
4. Bagged Tree\

Best Model was:**Random Forest Regression**

***This plot is the Feature Importance plotted for Random Forest Regression***

![Unknown-16](https://user-images.githubusercontent.com/31748299/121573736-6f29dc80-c9da-11eb-8f62-804189b68ca7.png)


***Recommendations:***
1. From the data and visualisations, it is seen that products with 'Low Fat' Content generate more revenue than Regualr. It is recommended that if the numebr of products with Lower Fat content are increases, overall sales would go up.
2. Item Visibility is another factor which boosts the sales of the items. It would help if visibility of the low selling items is increased and it will be interesting to see if the sales increase for those items. 
3. The factor that affects the most is the MRP of the item. MRP for some of the items can be increased to generate more sales. If the MRP is increased slightly, without causing the significant jump, it would not directly affect the consumer but in the long run, will give you more sales.
4. 






