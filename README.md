# Coursera-Peer-Graded-Assignment-Data-Science-With-Python for Coursera-IBM-Statistics-for-Data-Science-With-Python.
Project Case: Boston Housing Dat
Project was created using Anaconda Jupyter Notebook.  Watson Studio and Skills Network Editor rejected due to too many glitches or compatibility issues with the programs.

PROJECT INSTRUCTIONS:
Scenario: You are a Data Scientist with a housing agency in Boston MA, you have been given access to a previous dataset on housing prices derived from the U.S. Census Service to present insights to higher management. Based on your experience in Statistics, what information can you provide them to help with making an informed decision? Upper management will like to get some insight into the following.

1.  Is there a significant difference in the median value of houses bounded by the Charles river or not?
2.  Is there a difference in median values of houses of each proportion of owner-occupied units built before 1940?
3.  Can we conclude that there is no relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town?
4. What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner-occupied homes?

Using the appropriate graphs and charts, generate basic statistics and visualizations that you think will be useful for the upper management to give them important insight given the question they are asking, in your graphs, include an explanation of each statistic. 

OVERVIEW OF PROJECT TASKS
Final Project Tasks
Task 1: Familiarize yourself with the dataset 
Task 2: Generate basic statistics and visualizations for upper management. 
Task 3: Use the appropriate tests to answer the questions provided.
Task 4: Share your Jupyter Notebook

This project is worth 15% of your final grade. Detailed instructions for each of these tasks follow. 

TASK 1 BECOME FAMILIAR WITH THE DATASET
The following describes the dataset variables:

·      CRIM - per capita crime rate by town
·      ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
·      INDUS - proportion of non-retail business acres per town.
·      CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
·      NOX - nitric oxides concentration (parts per 10 million)
·      RM - average number of rooms per dwelling
·      AGE - proportion of owner-occupied units built prior to 1940
·      DIS - weighted distances to five Boston employment centres
·      RAD - index of accessibility to radial highways
·      TAX - full-value property-tax rate per $10,000
·      PTRATIO - pupil-teacher ratio by town
·      LSTAT - % lower status of the population
·      MEDV - Median value of owner-occupied homes in $1000's

This data was modified for this course and the link to the complete dataset can be found in the sklearn.datasets library

TASK 2: GENERATE DESCRIPTIVE STATISTICS AND VISUALIZATIONS
For all visualizations, please include a title in each graph and appropriate labels
Generate the following and explain your findings:
1. For the "Median value of owner-occupied homes" provide a boxplot
2. Provide a bar plot for the Charles river variable
3. Provide a boxplot for the MEDV variable vs the AGE variable. (Discretize the age variable into three groups of 35 years and younger, between 35 and 70 years and 70 years and older)
4. Provide a scatter plot to show the relationship between Nitric oxide concentrations and the proportion of non-retail business acres per town. What can you say about the relationship?
5. Create a histogram for the pupil to teacher ratio variable

TASK 3: USE THE APPROPRIATE TESTS TO ANSWER THE QUESTIONS PROVIDED.

For each of the following questions;
- Is there a significant difference in median value of houses bounded by the Charles river or not? (T-test for independent samples)
- Is there a difference in Median values of houses (MEDV) for each proportion of owner occupied units built prior to 1940 (AGE)? (ANOVA)
- Can we conclude that there is no relationship between Nitric oxide concentrations and proportion of non-retail business acres per town? (Pearson Correlation)
- What is the impact of an additional weighted distance to the five Boston employment centres on the median value of owner occupied homes? (Regression analysis)

Be sure to:
State your hypothesis.
Use α = 0.05
Perform the test Statistics.
State the conclusion from the test.
