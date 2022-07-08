---
layout: post
title: Data Science Interview Questions
date:  2016-01-28 10:18:00
tags: tutorials
subclass: 'post tag-tutorials'
categories: 'swati'
navigation: True
logo: 'assets/images/utilities/home_icon.png'
cover: 'assets/images/cover4.jpg'
---

Interview Questions :

1. How is logistic regression done?
Answer : Logistic regression measures the relationship between the dependent variable (our label of what we want to predict) and one or more independent variables (our features) by estimating probability using its underlying logistic function 

2. Differentiate between univariate, bivariate, and multivariate analysis. 
Answer : 1-Univariate data contains only one variable. The purpose of the univariate analysis is to describe   the data
         2-Bivariate data involves two different variables. The analysis of this type of data deals with causes and relationships and the analysis is done to determine the relationship between the two variables.

         3-Multivariate data involves three or more variables, it is categorized under multivariate. It is similar to a bivariate but contains more than one dependent variable.

3.  Write a basic SQL query that lists all orders with customer information.
Answer : Usually, we have order tables and customer tables that contain the following columns:

    	Order Table 
    	Orderid
    	customerId 
    	OrderNumber
    	TotalAmount
    	Customer Table 
    	Id
    	FirstName
    	LastName
    	City 
    	Country  
    	The SQL query is:
    	SELECT OrderNumber, TotalAmount, FirstName, LastName, City, Country
    	FROM Order
    	JOIN Customer
    	ON Order.CustomerId = Customer.Id

4. What is the goal of A/B Testing?
Answer : This is statistical hypothesis testing for randomized experiments with two variables, A and B. The objective of A/B testing is to detect any changes to a web page to maximize or increase the outcome of a strategy.

5. Why is R used in Data Visualization?
Answer : R is widely used in Data Visualizations for the following reasons-
         1.We can create almost any type of graph using R.
	     2.R has multiple libraries like lattice, ggplot2, leaflet, etc., and so many inbuilt functions as well.  
         3.It is easier to customize graphics in R compared to Python.
         4.R is used in exploratory data analysis.


6.  Between Python and R, which one would you pick for text analytics, and why?

Answer : For text analytics, Python will gain an upper hand over R due for the following reasons:

        The Pandas library in Python offers easy-to-use data structures as well as high-performance data analysis tools
        Python has a faster performance for all types of text analytics

7. What is the purpose of data cleaning in data analysis?
Answer : Cleaning data from different sources helps transform the data into a format that is easy to work 
         with
         Data cleaning increases the accuracy of a machine learning model.

8. Can you compare the validation set with the test set?

   Answer : A validation set is part of the training set used for parameter selection. It helps avoid overfitting the machine learning model being developed.
   A test set is meant for evaluating or testing the performance of a trained machine learning model.

9. 7. What are linear regression and logistic regression?

Answer : Linear regression is a form of statistical technique in which the score of some variable Y is          predicted  on the basis of the score of a second variable X, referred to as the predictor variable. The Y variable is known as the criterion variable.

Also known as the logit model, logistic regression is a statistical technique for predicting the binary outcome from a linear combination of predictor variables.

10. 


