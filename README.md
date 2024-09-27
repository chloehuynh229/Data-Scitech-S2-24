{\rtf1\ansi\ansicpg1252\cocoartf2513
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\froman\fcharset0 Times-Bold;\f1\froman\fcharset0 Times-Roman;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\qc\partightenfactor0

\f0\b\fs24 \cf2 \expnd0\expndtw0\kerning0
Assignment 1\
Predictive Modelling of Eating-Out problem 
\f1\b0 \
\pard\pardeftab720\partightenfactor0
\cf2 \

\f0\b Student\'92s name:
\f1\b0  Chloe Huynh\

\f0\b Student\'92s ID:
\f1\b0  u3245751\
\

\f0\b Objective
\f1\b0 \
\pard\pardeftab720\partightenfactor0
\cf0 \kerning1\expnd0\expndtw0 \
\pard\pardeftab720\partightenfactor0
\cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 In this assignment, I worked with a real-world dataset focused on Sydney restaurants. I applied feature engineering, modelling, and deployment techniques to obtain insights supported by code visualisations. I built predictive models and deployed my work to a public repository on GitHub and using Docker. Additionally, I utilized a Tableau Dashboard to visualize graphs for exploratory data analysis (EDA).\
\

\f0\b File Assignment_1_A.ipynb
\f1\b0 \
- Understand and \outl0\strokewidth0 Explore Data analysis of \outl0\strokewidth0 the dataset of Sydney restaurants;\
- Applied the matplotlib and seaborn to visualised charts to support the answers;\
- Produce Cuisine Density Map in which each subzone by the number of restaurants that serve a specific cuisine; and\
- Used Plotly to build an interactive plotting with Cuisine map and save it as an HTML file. \
\

\f0\b File Assignment_1_B.ipynb
\f1\b0 \
- Cleaned the dataset to prepare for the modelling step such as removing the NA value and unused variables;\
- Create feature engineering related to the target variable to improve the accuracy of the train model;\
- Encoder for each category variable before training the model;\
- Splitting data into 80% for training set and 20% for testing test;\
- Build a linear regression model and predict the test set;\
- Build another linear regression model (model 2) using the Gradient Descent as the optimisation function;\
- Calculate the mean square error (MSE) to compare the performance of both models;\
- Build a logistic regression model and confusion matrix to report the results on test data;\
- Draw a confusion matrix and observe the performance of the classification model;\
- Build three other different classification models to evaluate and compare the performance.\
\

\f0\b Folder data
\f1\b0 \
- file zomato_df_final_data.csv, which is the raw dataset used for this assignment; \
- file zamoto_df_clean.csv, which is the processed data and ready for training the model and for Tableau Dashboard;\
- sydney.geojson, which is the restaurant geographic information for producing the cuisine density map.\
\

\f0\b restaurant_distribution_by_cuisine.html - 
\f1\b0 The interactive plots allow users to explore Sydney restaurants with the option to filter by cuisine type. This feature enhances the analysis by enabling users to focus on specific culinary preferences, making it easier to visualize trends and patterns related to different cuisines.\
}