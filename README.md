# Telco Customer Churn Analysis and Prediction

## Introduction

This project focuses on predicting customer churn in a telecommunications company using machine learning. The objective is to identify customers who are likely to leave the service and provide actionable insights that can help improve customer retention strategies.

## Dataset

The dataset contains **7,043 customer records** with **21 features**, including customer demographics, subscribed services, billing information, contract details, and payment methods. The target variable is **Churn**, which indicates whether a customer has left the company.

**Dataset Source:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Data Cleaning

Data preprocessing included handling missing values, correcting data types, encoding categorical variables, and preparing the dataset for machine learning. Additional preprocessing techniques such as feature scaling and data transformation were also applied.

## Feature Engineering

New features including **AverageCharges**, **AboveAverageCharges**, **ServicesMost**, and a **K-Means Cluster** feature were created to capture customer behavior and improve model performance.

## Data Analysis

Exploratory Data Analysis (EDA) was performed to identify customer behavior patterns, analyze feature relationships, and discover key factors influencing customer churn through visualizations and statistical analysis.

## Modeling

The dataset was split into training and testing sets, and **ADASYN** was used to address class imbalance. An **XGBoost Classifier** was trained and evaluated using standard classification metrics to predict customer churn accurately.
