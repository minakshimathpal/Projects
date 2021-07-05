## Overview
Dataset - The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes. The data consists of Wine quality along with few features/variables that derive the quality IPL data consists of the performance metrics of each player such as score, Domain - Automobile, Manufacturing, Quality testing, Multimedia

### Skills and Tools

SVM, PCA, Classification, Python

## DOMAIN: 
Automobile(part 1) 
## CONTEXT: The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 
continuous attributes 
## DATA DESCRIPTION: The data concerns city-cycle fuel consumption in miles per gallon 
### Attribute Information: 
1. mpg: continuous
2. cylinders: multi-valued discrete
3. displacement: continuous
4. horsepower: continuous
5. weight: continuous
6. acceleration: continuous
7. model year: multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance) 
## PROJECT OBJECTIVE: Goal is to cluster the data and treat them as individual datasets to train Regression models to predict ‘mpg’ 
Steps and tasks: 
1. Import and warehouse data: 
• Import all the given datasets and explore shape and size. 
• Merge all datasets onto one and explore final shape and size.
• Export the final dataset and store it on local machine in .csv, .xlsx and .json format for future use.
• Import the data from above steps into python.
2. Data cleansing: 
• Missing/incorrect value treatment
• Drop attribute/s if required using relevant functional knowledge
• Perform another kind of corrections/treatment on the data.
3. Data analysis & visualisation:
• Perform detailed statistical analysis on the data.
• Perform a detailed univariate, bivariate and multivariate analysis with appropriate detailed comments after each analysis. 
Hint: Use your best analytical approach. Even you can mix match columns to create new columns which can be used for better analysis. Create 
your own features if required. Be highly experimental and analytical here to find hidden patterns.
4. Machine learning:
• Use K Means and Hierarchical clustering to find out the optimal number of clusters in the data. 
• Share your insights about the difference in using these two methods. 
5. Answer below questions based on outcomes of using ML based methods. 
• Mention how many optimal clusters are present in the data and what could be the possible reason behind it.
• Use linear regression model on different clusters separately and print the coefficients of the models individually
• How using different models for different clusters will be helpful in this case and how it will be different than using one single model without 
clustering? Mention how it impacts performance and prediction.
6. Improvisation: 
• Detailed suggestions or improvements or on quality, quantity, variety, velocity, veracity etc. on the data points collected by the company to 
perform a better data analysis in future

## • DOMAIN: Manufacturing(part 2)
• CONTEXT: Company X curates and packages wine across various vineyards spread throughout the country.
• DATA DESCRIPTION: The data concerns the chemical composition of the wine and its respective quality.
Attribute Information: 
1. A, B, C, D: specific chemical composition measure of the wine
2. Quality: quality of wine [ Low and High ]
• PROJECT OBJECTIVE: Goal is to build a synthetic data generation model using the existing data provided by the company.
Steps and tasks: 
1. Design a synthetic data generation model which can impute values [Attribute: Quality] wherever empty the company has missed recording the data.

## DOMAIN: Automobile (part 3)
## CONTEXT: 
The purpose is to classify a given silhouette as one of three types of vehicle, using a set of features extracted from the silhouette. 
The vehicle may be viewed from one of many different angles.
## DATA DESCRIPTION: 
The data contains features extracted from the silhouette of vehicles in different angles. Four "Corgie" model vehicles 
were used for the experiment: a double decker bus, Cheverolet van, Saab 9000 and an Opel Manta 400 cars. This particular combination of 
vehicles was chosen with the expectation that the bus, van and either one of the cars would be readily distinguishable, but it would be more 
difficult to distinguish between the cars.
• All the features are numeric i.e. geometric features extracted from the silhouette.
## PROJECT OBJECTIVE: 
Apply dimensionality reduction technique – PCA and train a model using principal components instead of training the 
model using just the raw data.
Steps and tasks: 
1. Data: Import, clean and pre-process the data
2. EDA and visualisation: Create a detailed performance report using univariate, bi-variate and multivariate EDA techniques. Find out all possible hidden 
patterns by using all possible methods.
For example: Use your best analytical approach to build this report. Even you can mix match columns to create new columns which can be used 
for better analysis. Create your own features if required. Be highly experimental and analytical here to find hidden patterns. 
3. Classifier: Design and train a best fit SVM classier using all the data attributes.
4. Dimensional reduction: perform dimensional reduction on the data.
5. Classifier: Design and train a best fit SVM classier using dimensionally reduced attributes.
6. Conclusion: Showcase key pointer on how dimensional reduction helped in this case
