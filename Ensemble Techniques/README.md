## Overview
The project was accomplished by deploying a GUI powered by supervised learning and ensemble modeling techniques to build and train a prediction model for a telecom company. This will help them identify the potential customers who have a higher probability to churn. This will enable the company to understand and pinpoints the patterns of customer churn and increase the focus on customer retention strategies. Dataset – The dataset consists of various features of the customer

### Skills and Tools

EDA, Logistic Regression, Decision tree, Random forest

## DOMAIN:(part 1)
Telecom
## CONTEXT: 
A telecom company wants to use their historical customer data to predict behaviour to retain customers. You can 
analyse all relevant customer data and develop focused customer retention programs.
## DATA DESCRIPTION: 
Each row represents a customer, each column contains customer’s attributes described on the column 
Metadata. The data set includes information about:
• Customers who left within the last month – the column is called Churn

• Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device 
protection, tech support, and streaming TV and movies

• Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly 
charges, and total charges

• Demographic info about customers – gender, age range, and if they have partners and dependents

## PROJECT OBJECTIVE: 
Build a model that will help to identify the potential customers who have a higher probability to churn. 
This help the company to understand the pinpoints and patterns of customer churn and will increase the focus on strategising 
customer retention
Steps to the project:
1. Import and warehouse data: 
• Import all the given datasets from MYSQL server. Explore shape and size. 
• Merge all datasets onto one and explore final shape and size.
2. Data cleansing: 
• Missing value treatment
• Convert categorical attributes to continuous using relevant functional knowledge
• Drop attribute/s if required using relevant functional knowledge
• Automate all the above steps
3. Data analysis & visualisation:
• Perform detailed statistical analysis on the data.
• Perform a detailed univariate, bivariate and multivariate analysis with appropriate detailed comments after each analysis. 
4. Data pre-processing: 
• Segregate predictors vs target attributes
• Check for target balancing and fix it if found imbalanced.
• Perform train-test split.
• Check if the train and test data have similar statistical characteristics when compared with original data.
5. Model training, testing and tuning: 
• Train and test all ensemble models taught in the learning module.
• Suggestion: Use standard ensembles available. Also you can design your own ensemble technique using weak classifiers.
• Display the classification accuracies for train and test data.
• Apply all the possible tuning techniques to train the best model for the given data. 
• Suggestion: Use all possible hyper parameter combinations to extract the best accuracies. 
• Display and compare all the models designed with their train and test accuracies.
• Select the final best trained model along with your detailed comments for selecting this model. 
• Pickle the selected model for future use.
6. GUI development:
• Design a clickable GUI desk application or web service application.
• This GUI should allow the user to input all future values and on a click use these values on the trained model above to predict.
• It should display the prediction.
7. Conclusion and improvisation: 
• Write your conclusion on the results.
• Detailed suggestions or improvements or on quality, quantity, variety, velocity, veracity etc. on the data points collected by the 
telecom operator to perform a better data analysis in future


