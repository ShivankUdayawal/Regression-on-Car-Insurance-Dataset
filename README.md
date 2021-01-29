# Regression-on-Car-Insurance-Dataset
## Predicting for Customers, whether they will buy car insurance or not.

### The terminology will often listen related to regression analysis is :

* Dependent variable or target variable : Variable to predict.

* Independent variable or predictor variable : Variables to estimate the dependent variable.

* Outlier : Observation that differs significantly from other observations. It should be avoided since it may hamper the result.

* Multicollinearity : Situation in which two or more independent variables are highly linearly related.

* Homoscedasticity or homogeneity of variance : Situation in which the error term is the same across all values of the independent variables.


Logistic Regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).


* First, binary logistic regression requires the dependent variable to be binary and ordinal logistic regression requires the dependent variable to be ordinal.

* Second, logistic regression requires the observations to be independent of each other. In other words, the observations should not come from repeated measurements or matched data.

* Third, logistic regression requires there to be little or no multicollinearity among the independent variables. This means that the independent variables should not be too highly correlated with each other.

* Fourth, logistic regression assumes linearity of independent variables and log odds. although this analysis does not require the dependent and independent variables to be related linearly, it requires that the independent variables are linearly related to the log odds.

* Finally, logistic regression typically requires a large sample size. A general guideline is that you need at minimum of 10 cases with the least frequent outcome for each independent variable in your model.

### Introduction

* This notebook is going to be focused on solving the problem of predicting whether a Customers, whether they will buy car insurance or not.

* Here, I will go through the whole process of creating a machine learning model on the famous "carInsurance dataset" , which is used by many people all over the world.

* We have general information about clients (age, job, etc.) as well as more specific information about the current insurance sell campaign (communication, last contact day) and previous campaigns (attributes like previous attempts, outcome).


### Business Problem

In this competitive business environment, Insurance companies are adopting aggressive marketing strategies for new customer acquisition and existing customer retention. To adapt to the changing market landscape, an organization must monitor changes in buying patterns and behavior of the customers based on various demographics, geographies & psychographics profile. The analysis of existing customer’s data can through many insights of the customer such as their buying behavior, buying Pattern, brand loyalty, investment pattern & customer churn. Such insight can be of great help to Marketing Head while devising new Marketing strategy.

While embracing digital is integral to competing in the market, consumers still heavily rely on the human, one-on-one service that only agents are able to provide. Great customer service is foundational for all agents. Providing the ideal mix of technology solutions and personal interaction should be at the center of an agency’s planning process as it prepares to meet customer demands and increase growth and retention.

NationWide Bank in the United States, Besides usual services, this bank also provides car insurance services. The bank organizes regular campaigns to attract new clients. The bank has potential customers’ data, and bank’s employees call them for advertising available car insurance options.

At NationWide (https://www.nationwide.com/) the mission is to help people and businesses prosper. NationWide is always looking for ways to help our customers understand their financial health and identify which products and services might help them achieve their monetary goals. Their data science team is continually challenging our machine learning algorithms, working with the global data science community to make sure we can more accurately identify new ways to solve our most common challenge.

Can we help the Marketing head with some kind of technology solutions which can enable planning process as it prepares to meet customer demands and increase growth and retention?

We are provided with general information about clients (age, job, etc.) as well as more specific information about the current insurance sell campaign (communication, last contact day) and previous campaigns (attributes like previous attempts, outcome).

You have data about 4000 customers who were contacted during the last campaign and for whom the results of campaign (did the customer buy insurance or not) are known. Let us build machine learning model to help NationWide.


### Data Visualization

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/Age.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/carinsurance.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/job.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/education.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/marital.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/agewithinscurance.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/jobwithinscurance.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/educationwithinscurance.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/maritalwithinscurance.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/pairplot.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/heatmap.png)

![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/confusionmatrix.png)


![](https://github.com/ShivankUdayawal/Regression-on-Car-Insurance-Dataset/blob/main/Data%20Visualization/Roc.png)







