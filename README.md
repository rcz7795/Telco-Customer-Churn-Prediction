# Telecom-Customer-Churn-Prediction

![ML](https://img.shields.io/badge/ML-Classification-blue.svg) 

![logo](Screenshots/Airbnb.png)

## Project Objective:
The objective of the project is to create a machine learning model. We are doing a supervised learning and our aim is to do predict customer churn.

## Problem Statement:
Churn quantifies the number of customers who have unsubscribed or canceled their service contract. Customers turning their back to your service or product are no fun for any business. It is very expensive to win them back once lost, not even thinking that they will not do the best word to mouth marketing if unsatisfied.

The basic layer for predicting future customer churn is data from the past. We look at data from customers that already have churned (response) and their characteristics / behaviour (predictors) before the churn happened.

In our case the objective is reducing customer churn by identifying potential churn candidates beforehand, and take proactive actions to make them stay.

## Data Collection:
The dataset is obtained from Kaggle. 
Link: https://www.kaggle.com/blastchar/telco-customer-churn

## Modelling:
The analysis and model creation can be found in the .ipynb file. 

The main packages used are numpy, pandas, matplotlib, seaborn and sklearn.  

## Deployemnt:
The web app has been build using basic HTML, CSS, Javascript, Flask and Herkou.

Link: https://airbnb-rental-price-predict.herokuapp.com/

![ML](Screenshots/AirbnbPricing.JPG)

## Requirements Installation:
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Future Scope:
* Use multiple Algorithms
* Optimize Flask app.py
* Update the Front-End 
