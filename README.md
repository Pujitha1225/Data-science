1. Excel Project: 

Expected Deliverables:  Design a sales dashboard that analyzes the sales based on various product categories. The company wants to add user control for product category so that users can select a category and can see the trend month-wise and product-wise accordingly.

2. SQL Project:
 Focus on identifying the regular customers to provide offers, analyze the busiest route which helps to increase the number of aircraft required and prepare an analysis to determine the ticket sales details. This will ensure that the company improves its operability and becomes more customer-centric and a favorable choice for air travel.

3. Python Project:
 
 DESCRIPTION

You've been asked to perform data analysis of service request (311) calls from New York City. You've also been asked to utilize data wrangling techniques to understand the pattern in the data and visualize the major types of complaints.

 

Note: Download 311-service-requests-nyc.zip file using the link given in the Customer Service Requests Analysis project problem statement and extract the 311_Service_Requests_from_2010_to_Present.csv file

 

Perform the following steps:

Understand the dataset:
Identify the shape of the dataset
Identify variables with null values
2. Perform basic data exploratory analysis:

Utilize missing value treatment
Analyze the date column and remove the entries if it has an incorrect timeline
Draw a frequency plot for city-wise complaints
Draw scatter and hexbin plots for complaint concentration across Brooklyn
3. Find major types of complaints:

Plot a bar graph of count vs. complaint types
Find the top 10 types of complaints
Display the types of complaints in each city in a separate dataset
 

4. Visualize the major types of complaints in each city

5. Check if the average response time across various types of complaints

6. Identify significant variables by performing a statistical analysis using p-values and chi-square values.


   4. Machine learning Project:
  
focus on improving the user experience by personalizing it to the user's needs. You have to model a recommendation engine so that users get recommendations for books based on the behavior of similar users. This will ensure that users are renting the books based on their tastes and traits.

Note: You have to perform user-based collaborative filtering and item-based collaborative filtering.

Dataset description:

BX-Users: It contains the information of users.

user_id - These have been anonymized and mapped to integers

Location - Demographic data is provided

Age - Demographic data is provided

If available, otherwise, these fields contain NULL-values.

 

BX-Books: 

isbn - Books are identified by their respective ISBNs. Invalid ISBNs have already been removed from the dataset.

book_title

book_author

year_of_publication

publisher


 

BX-Book-Ratings: Contains the book rating information. 

user_id

isbn

rating - Ratings (`Book-Rating`) are either explicit, expressed on a scale from 1–10 (higher values denoting higher appreciation), or implicit, expressed by 0.

 

Note: Download the “BX-Book-Ratings.csv”, “BX-Books.csv”, “BX-Users.csv”, and “Recommend.csv” using the link given in the Book Rental Recommendation project problem statement.

 

Following operations should be performed:

Read the books dataset and explore it

Clean up NaN values

Read the data where ratings are given by users

Take a quick look at the number of unique users and books

Convert ISBN variables to numeric numbers in the correct order

Convert the user_id variable to numeric numbers in the correct order

Convert both user_id and ISBN to the ordered list, i.e., from 0...n-1

Re-index the columns to build a matrix

Split your data into two sets (training and testing)

Make predictions based on user and item variables

Use RMSE to evaluate the predictions.

5. Tableau Project:

   The company is expanding and wants to open new branches in various parts of the world. Your task is to compare various parameters such as income, life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio of different countries using the sample insurance dataset and world development indicators dataset.

 

Objective: 

Create a dashboard to compare all the parameters mentioned above for different countries, to strategize market penetration and to target new customers.

Datasets:

Primary Dataset – Insurance Sample Dataset

Secondary Dataset – Global Financial Development Database

Note: Use Data Blending with Relationships between Country Code, Country, and Year

Steps to Perform: 
Create a geographic map showing the countries' fields. Color the map based on the income column from the secondary dataset
Include income group filter in the dashboard
Include a webpage to show data from the world bank webpage driven by an URL action from a geography graph
The country names in the map will act as the trigger
https://en.wikipedia.org/wiki/Country
Create a KPI Table to show the comparison between the selected period and the period prior to the selected one
Create two parameters for Year Selection and Category Selection
Category parameter includes life insurance share, market share, penetration, ratio of reinsurance accepted, and retention ratio
Create a calculated field to calculate the Growth %
Create a table to show these values
Title should be updated based on the category selection
Create Growth Indicator Shapes based on the Growth %
Growth indicator displays Negative, No Change, and Positive as values and corresponding shapes against it
Create a trend line to show the selected category values The line shows an arrow or triangle at the last mark
Create a dashboard filter for income group to be applied for all charts with the filter action enabled in the map as well
Formatting should be done appropriately
Sample output:
Graphical user interface, application Description automatically generated.

6. Capstone Project:

   Problem Statement
NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates knowledge about and treatments for the most chronic, costly, and consequential diseases.
The dataset used in this project is originally from NIDDK. The objective is to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
Build a model to accurately predict whether the patients in the dataset have diabetes or not.
Dataset Description
The datasets consists of several medical predictor variables and one target variable (Outcome). Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

 

Variables	Description
Pregnancies	Number of times pregnant
Glucose	Plasma glucose concentration in an oral glucose tolerance test
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Triceps skinfold thickness (mm)
Insulin	Two hour serum insulin
BMI	Body Mass Index
DiabetesPedigreeFunction	Diabetes pedigree function
Age	Age in years
Outcome	Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0
Project Task: Week 1
Data Exploration:

1. Perform descriptive analysis. Understand the variables and their corresponding values. On the columns below, a value of zero does not make sense and thus indicates missing value:

• Glucose

• BloodPressure

• SkinThickness

• Insulin

• BMI

2. Visually explore these variables using histograms. Treat the missing values accordingly.

3. There are integer and float data type variables in this dataset. Create a count (frequency) plot describing the data types and the count of variables. 

Project Task: Week 2
Data Exploration:

1. Check the balance of the data by plotting the count of outcomes by their value. Describe your findings and plan future course of action.

2. Create scatter charts between the pair of variables to understand the relationships. Describe your findings.

3. Perform correlation analysis. Visually explore it using a heat map.

 

Project Task: Week 3
Data Modeling:

1. Devise strategies for model building. It is important to decide the right validation framework. Express your thought process.

2. Apply an appropriate classification algorithm to build a model. Compare various models with the results from KNN algorithm.

 

Project Task: Week 4

Data Modeling:

1. Create a classification report by analyzing sensitivity, specificity, AUC (ROC curve), etc. Please be descriptive to explain what values of these parameter you have used.

Data Reporting:

2. Create a dashboard in tableau by choosing appropriate chart types and metrics useful for the business. The dashboard must entail the following:

a. Pie chart to describe the diabetic or non-diabetic population

b. Scatter charts between relevant variables to analyze the relationships

c. Histogram or frequency charts to analyze the distribution of the data

d. Heatmap of correlation analysis among the relevant variables

e. Create bins of these age values: 20-25, 25-30, 30-35, etc. Analyze different variables for these age brackets using a bubble chart.
