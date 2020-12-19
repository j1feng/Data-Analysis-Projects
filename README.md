# Data_analysis_projects

A few of the data analysis projects for practice that I have done at UCSD; There are other data science projects that I made that are not included in this repository;

## Project 3: Beijing PM2.5 Linear Regression

Date: December 2020

- Predict the amount of PM2.5 concentration at Beijing given date and weather variables; Practice of data visualization and feature selection;


## Project 2: Snapchat Political Advertisement Analysis

Date: March 2020

- The datasets come from https://www.snap.com/en-US/political-ads/. The first part of the project is simply data cleaning and exploratory data analysis. The data set does not contains many numeric columns: it has over 30 columns, yet it really has two quantitative variables before cleaning: the Spend column, and the Impression columns. Before writing any codes or doing any further investigation, we think that there is a relationship between its columns, for example, the amount (In local currency) spent by the advertiser over the campaign (up to the current date), and the number of times the Ad has been viewed by Snapchatters.

- Spend would be a good dependent variable X and when impression is the dependent variable Y, what we try to predict. Because to think about it, the goal of these advertisement is to persuade more people to vote or pay attention to some campaigns, and it is quite important, and to the benefit of the compaign, to make more impressions. To make snapchat put their ads longer, or to recommend the ads to more people, the companies or organization should pay more. Think about Mike Bloomberg, the American business man who ran for the president in 2020. He spent around 300 million US dollars in his compaign. As a result, he is often seen on the ads on all the platform. (Ask a friend if he/she has saw Mike Bloomberg in an ads before). Besides spend, we will include more features to help predict the Impression, such as gender, region, age... etc.

- It would be useful for these organization to decide how many to spend in order to meet their goal of impressions. We will make such model to predict the impression (target variable). Since the number of impression is a numberic, it is not a classfication problem, but a regression problem. The evaluation metric we can use for this regression model will be mainly R² or sometimes Coefficient of Determination, and Root-Mean-Squared-Error(RMSE).
  
  
## Project 1: cardiovascular_disease_project

Date: December 2019

- Final project for COGS 108 Data science in practice in fall 2019. A data analysis and classfication project on the data of cardiovascular disease.

- In this project, we analyzed data of patients who have been diagnosed with cardiovascular disease to further understand the causes of cardiovascular disease as well as to develop an algorithm that is able to non-invasively predict and predict and diagnose such conditions. First, we explored and visualized the distributions of different features in the dataset, including age, BMI, systolic, and diastolic blood pressure. Secondly, we evaluate and compare different classifiers (Linear Regression, Logistic Regression, Principle Component Analysis, and Support Vector Machines) and identify which is best able to predict cardiovascular disease in this dataset.
