# Salary Estimate Prediction Project

#Overview

The Salary Estimate Prediction Project is a data analysis and machine learning project designed to predict salaries for data-related positions based on location, company reviews, and job titles. This project aims to help job seekers and employers gain insights into salary expectations for data-related roles.

#Table of Contents

Objective

Data Preparation

Data Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Modeling

Prediction

Model Saving

#Objective

The main goal of this project is to predict the salaries of data-related positions using a machine learning model. The prediction is based on various factors, including job title, location, company reviews, and other features.

#Data Preparation

In this section, the project starts by importing the dataset and necessary libraries for data analysis and modeling. The dataset used for this project is loaded from an external source.

#Data Cleaning

The data cleaning phase involves several important steps:

Creation of minimum and maximum salary columns by parsing values from the "Salary Estimate" column.
Calculation of an average salary column.
Extraction of the state where each position is located, creating a state column.
Organizing job titles into categories for better analysis.

#Exploratory Data Analysis (EDA)

This section explores the cleaned dataset using various data visualization techniques:

Pairplots to visualize relationships between variables.
Distribution plots for average salary and company ratings.
A count plot to show the distribution of job titles.
Scatterplots to visualize the relationship between company ratings and average salary, categorized by job title.

#Feature Engineering

Feature engineering involves transforming categorical variables into a format suitable for machine learning. In this project, one-hot encoding is applied to job titles and states.

#Modeling

The modeling phase utilizes a linear regression model to predict average salaries based on the selected features. The data is split into training and testing sets to evaluate the model's performance.

#Prediction

The model predicts salaries for data-related positions based on the selected features.

#Model Saving

The trained linear regression model is saved using the Pickle library, which allows it to be loaded and used for salary predictions in the future.

This project provides valuable insights into salary expectations for data-related roles and can be a helpful tool for both job seekers and employers in the field.

If you have any questions, feedback, or would like to contribute to the project, please feel free to reach out or submit a pull request. We hope this project helps you in your career decisions and salary negotiations.
