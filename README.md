# ECS171_GroupProject
ECS171 - Group Project Abstract
 
Group members:
Oscar Hernandez, Caroline Li, Mardan Mahmut, Matthew Schulz, Rishi Thakkar

Data source: https://archive.ics.uci.edu/ml/datasets/Wine+Quality 
(Red wine only)

Data Features :
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulfates
11 - alcohol
12 - quality (score between 0 and 10)

This data on red wine was gathered in Northern Portugal. It contains physicochemical qualities of wine as well as a subject value on quality ranging from 0-10.  We can create a model that uses the physicochemical attributes to determine whether a red wine will be good or not. 
To determine whether or not wine is good we will convert quality values to 1 if they are above a threshold such as 7 or 8, and if they are below convert them to 0. We will then use logistic regression to create a model that can predict quality. Furthermore, we can create a correlation matrix and model coefficients on a scatterplot to see which attributes strongly affect the taste of red wine. 
This model can be used to determine which factors significantly influence the quality of red wine to improve flavor and can help create a guideline on what values each component should have. Also, if the wine were to taste bad, then these attributes could be checked under the model to determine which characteristic is negatively affecting the flavor. Another model can be created using polynomial regression, which could determine the attribute with the highest correlation to quality as well.

