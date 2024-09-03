# British Airways Data Science Assignment

## Overview

This repository contains the work I completed as part of the British Airways Data Science virtual internship provided by Forage. The program involved two key tasks focused on utilizing data science to derive insights from customer data and predict booking behavior, especially during peak travel seasons. This README provides an overview of the project structure, tasks completed, tools used, and the insights gained.

## Task Descriptions

### Task 1: Customer Sentiment Analysis

**Objective**: To understand customer opinions and sentiment towards British Airways by scraping, cleaning, and analyzing third-party data.

- **Data Scraping**: Utilized Python's `BeautifulSoup` and `requests` libraries to scrape customer reviews from relevant websites.
- **Data Cleaning**: Employed `pandas` and `numpy` for cleaning the scraped data, including handling missing values, removing duplicates, and normalizing text.
- **Sentiment Analysis**: Applied Natural Language Processing (NLP) techniques using `NLTK` and `TextBlob` to determine customer sentiment. Visualizations were created using `matplotlib` and `seaborn`.

### Task 2: Predictive Modeling of Holiday Bookings

**Objective**: To forecast the number of seats British Airways will sell during the holiday travel season.

- **Data Preparation**: Cleaned and preprocessed the provided dataset, handling missing values, encoding categorical variables, and normalizing features.
- **Feature Engineering**: Created new features such as customer loyalty score, previous booking patterns, and seasonality indicators to improve model accuracy.
- **Model Training**: Trained a RandomForest classifier using `scikit-learn` to predict customer bookings. The model's hyperparameters were tuned using GridSearchCV for optimal performance.
- **Model Evaluation**: Assessed model performance using metrics such as accuracy, precision, recall, and the F1-score. The feature importance was analyzed to understand which variables most influenced the predictions.

## Tools and Technologies Used

- **Programming Language**: Python
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `BeautifulSoup`, `NLTK`, `TextBlob`, `matplotlib`, `seaborn`
- **Modeling**: RandomForest, GridSearchCV
- **Visualization**: Matplotlib, Seaborn

## Insights and Learnings

- **Customer Sentiment**: The sentiment analysis revealed key areas where British Airways could improve customer satisfaction, particularly in service quality and on-time performance.
- **Predictive Modeling**: The RandomForest model provided valuable insights into booking behaviors, with variables like previous booking history and customer loyalty showing significant predictive power.
- **Feature Engineering**: Creating seasonality and loyalty-based features significantly boosted the model's accuracy, highlighting the importance of domain-specific feature engineering.

## Conclusion

This project provided hands-on experience with real-world data science tasks, from data cleaning and analysis to predictive modeling. The insights generated from the data could help British Airways make data-driven decisions to enhance customer satisfaction and optimize booking strategies.
