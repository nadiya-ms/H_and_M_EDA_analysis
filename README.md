# H&M Exploratory data analysis (EDA)
<img src="./images/H_M-Logo.svg">
This repository contains a Jupyter Notebook that provides a detailed Exploratory Data Analysis (EDA) and implements Collaborative Filtering for recommendation systems. These systems detect similar criteria that characterize customers, allowing for the advertisement of similar products to those customers.

## Overview
H&M Group is a family of brands and businesses with 53 online markets and approximately 4,850 stores. Our online store offers shoppers an extensive selection of products to browse through. But with too many choices, customers might not quickly find what interests them or what they are looking for, and ultimately, they might not make a purchase. To enhance the shopping experience, product recommendations are key. More importantly, helping customers make the right choices also has a positive implications for sustainability, as it reduces returns, and thereby minimizes emissions from transportation.

In this project the product recommendations based on data from previous transactions, as well as from customer and product meta data were developed.

## Data
The raw data for this project can be accessed [here](https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations).

### Data Analysis steps flow:
##### 1. Articles Dataset:
- Product Category Analysis
- Category Analysis by Product Section
- Product Type Analysis
- Product Graphic Element Analysis
- Product Color Analysis

##### 2. Customers Dataset:
- Data Anomaly
- Customer Age Analysis
- H&M Club Status Analysis
- Message Sending Frequency Analysis

##### 3. Transactions Dataset:
- Purchase Value Analysis
- Value Outliers
- Frequent Buyers Analysis
- Purchase Value Analysis within a Group
- Value Analysis by Time

##### 4. Collaborative Filtering Recommendation System:
- Cosine Similarity
- Getting Recommendations for a Customer

## Prerequisites
To run this notebook, you will need:
* Python 3.x
* Jupyter Notebook
* Required Python libraries: pandas, numpy, matplotlib, seaborn, stqdm

## How to Run
* Clone this repository to your local machine.
* Navigate to the project directory.
* Install the required packages.
* Open Jupyter Notebook.
* Navigate to the notebook file and open it.
* Run the cells to see the analysis.
