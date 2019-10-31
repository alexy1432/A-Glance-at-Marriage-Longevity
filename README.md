"# Project3"

Marriage is the ultimate goal for many individuals and the harsh reality is, it doesn't work out for a significant amount of couples.
What are the keys to a lasting marriage? 

The goal of this project is to apply machine learning to a dataset that keep tracks of married individuals:
Country of Origin, Sex, Age, Marriage duration, Number of Children, Number of brought up children, Education level,
Material Satisfaction, Religion, Religiosity, Prenup Agreement Level, and Marriage Satisfaction.

The data was taken from 33 countries. Each country had their own specialized local research team in order to prevent any 
language barriers. The most common survey areas were either higher learning schools or workplace environments.
All participants took the survey voluntarily and had 30 minutes to complete.

We want to apply all of the mentioned factors in order to test for an impact on an individual's marriage duration.
Applying Tensorflow and Sklearn will make it possible to plug in this data in order to predict the impacts of each
feature on marriage duration. We want to set up a supervised learning environment in order to 
create a regression analysis.

We first want to numerically categorize our X values using the get_dummies function. Then we want to split 
our data into training and testing data. Next, we wanat fit our model - which makes our data
readable by the algorithm. Finally, we execute the machine learning algorithm. 

The results were better than expected. The R-Squared value was ~.82, which means that 82% of our observed
values align with the predicted regression line. Then we observed the predicted Y values and they also
align well with the actual Y values, which means the algorithm was successful. 

We then wanted to look at the weighting of each feature - meaning the impact each feature had in regards to
marriage duration. Having no education, being Hindu, or Protestent led to the longest lasting marriages.
Being Evangelic, having a Master's Degree, and being Spiritualist all led to the shortest lasting marriages.

Each country also had their own trends of marriage duration. Italy had the longest lasting marriages and India had the shortest.
Upon comparing the features of Italy and India, the sample populations in Italy were 10-20 years older than those in India. The top 
and bottom 5 countries were also compared and no significant relationships were found.
Because the dataset only surveyed married people - and not divorced, this limited many conclusions. We can only conclude that 
age was the defining factor in marriage duration.






