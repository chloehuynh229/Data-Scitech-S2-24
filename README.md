# Data-Scitech
Assignment_1

## Objective

In this assignment, I worked with a real-world dataset focused on Sydney restaurants. I applied feature engineering, modelling, and deployment techniques to obtain insights supported by code visualisations. I built predictive models and deployed my work to a public repository on GitHub and using Docker. Additionally, I utilized a Tableau Dashboard to visualize graphs for exploratory data analysis (EDA).

## File Assignment_1_A.ipynb
- Understand and Explore Data analysis of the dataset of Sydney restaurants;
- Applied the matplotlib and seaborn to visualised charts to support the answers;
- Produce Cuisine Density Map in which each subzone by the number of restaurants that serve a specific cuisine; and
- Used Plotly to build an interactive plotting with Cuisine map and save it as an HTML file. 

## File Assignment_1_B.ipynb
- Cleaned the dataset to prepare for the modelling step such as removing the NA value and unused variables;
- Create feature engineering related to the target variable to improve the accuracy of the train model;
- Encoder for each category variable before training the model;
- Splitting data into 80% for training set and 20% for testing test;
- Build a linear regression model and predict the test set;
- Build another linear regression model (model 2) using the Gradient Descent as the optimisation function;
- Calculate the mean square error (MSE) to compare the performance of both models;
- Build a logistic regression model and confusion matrix to report the results on test data;
- Draw a confusion matrix and observe the performance of the classification model;
- Build three other different classification models to evaluate and compare the performance.

## Folder data
- file zomato_df_final_data.csv, which is the raw dataset used for this assignment; 
- file zamoto_df_clean.csv, which is the processed data and ready for training the model and for Tableau Dashboard;
- sydney.geojson, which is the restaurant geographic information for producing the cuisine density map.

## restaurant_distribution_by_cuisine.html
The interactive plots allow users to explore Sydney restaurants with the option to filter by cuisine type. This feature enhances the analysis by enabling users to focus on specific culinary preferences, making it easier to visualize trends and patterns related to different cuisines.
