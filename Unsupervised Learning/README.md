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
## PROJECT OBJECTIVE: 
Goal is to cluster the data and treat them as individual datasets to train Regression models to predict ‘mpg’ 

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


## • DOMAIN: Sports management(part 4) 
## CONTEXT: 
Company X is a sports management company for international cricket. 
## DATA DESCRIPTION: 
The data is collected belongs to batsman from IPL series conducted so far. Attribute Information: 
1. Runs: Runs score by the batsman
2. Ave: Average runs scored by the batsman per match
3. SR: strike rate of the batsman
4. Fours: number of boundary/four scored
5. Six: number of boundary/six scored
6. HF: number of half centuries scored so far
## PROJECT OBJECTIVE:
Goal is to build a data driven batsman ranking model for the sports management company to make business decisions.



