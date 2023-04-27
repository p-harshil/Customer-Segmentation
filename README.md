# Predictive-Analysis

### Overview:
The Predictive Analaysis (Task - 2) is a part of the Data@ ANZ Virtual Internship program which was offered by Forage (formerly Sherpa). This program consisted of 2 tasks
- Exploratory Data Analysis
- Predictive Modeling
<p>One of the main focuses of this project is to predict the annual salary of each customer using the same transaction dataset. We will explore correlations between annual salary and various customer attributes such as age, purchasing behavior, and other readily available data.
<p>In addition to exploring the data, we will build a simple regression model to predict the annual salary for each customer. For a challenge, we can build a decision tree-based model to predict salary and compare its performance to the regression model.

### About Dataset:
This project is based on a synthesized transaction dataset containing 3 months' worth of transactions for 100 hypothetical customers. The dataset includes purchases, recurring transactions, and salary transactions and is designed to simulate realistic transaction behaviors observed in ANZ's real transaction data. The dataset is provided by ANZ itself, in the form of excel file, for the program on Forage platform.
<p> Here is the snapshot of the dataset to get an idea: </br>
![image](https://user-images.githubusercontent.com/68314057/234981410-6591d47c-1209-498c-a87b-d2c63f720317.png)

### Dependecies:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

### Prediction: 
- Customers 'annual salary' is predicted using regression and segmentation is predicted using classification algorithm. Decision tree-based model results in accuracy of 75% in classification and 68% in regression.

### Future work:
As this is an introductory staged predicitve analysis work, many changes are expected to improve the analysis, performance and more robust system. 
- This project implemented OHE to convert catagorical variables in indicator variables. Creating new features from the existing ones to should be carried out for improved accuracy.
- Ensemble Methods should be used to combine multiple models for better prediction.
- Model should be tuned using hyperparamters with the help of GridSearch or RandomSearch algorithms. 
- Detailed analysis of the data required to understand data distribution and handle it causing to provide false prediction.

### Instructions:
To run this project, the required libraries must be installed. You must enroll in the internship program provided by Forage platform to access the dataset. Unfortunately, this specific program of ANZ has been discontinued from the Platform. However, one can find many other programs to practice the data and predictive analytics using real time data.
