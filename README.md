# Online Shoppers Intention Prediction

## Overview

- **Domain:** Machine Learning
- **Languages:** Python

In this project, we have developed a machine learning model to predict whether an online shopper will make a purchase or not. Understanding and predicting online shopper intent can be invaluable for businesses, as it can help them optimize their marketing strategies.

## Project Goals

- Build a machine learning model that predicts online shopper intention.
- Demonstrate proficiency in machine learning algorithms and data analysis.
- Apply machine learning techniques to a real-world problem in the e-commerce domain.

## Key Features

- Utilized a diverse set of machine learning algorithms, including K-means Clustering, Random Forests, and Gradient Boosting, to train and evaluate the model's performance.
- Conducted thorough data analysis to identify relevant features and patterns in the dataset.
- Implemented best practices in preprocessing, including data cleaning, feature engineering, and handling imbalanced data.
- Evaluated the model using appropriate performance metrics, such as accuracy, precision, recall, and F1-score.
- Visualized results and insights for better understanding.



### Explore the Jupyter notebooks to understand the data analysis and model development process.



## Data

The dataset used for this project is available in the `C:\Users\91630\Desktop\Devs\ML\Online-Shoppers-Purchasing-Intention-master\online_shoppers_intention.csv` directory.**Attribute Information:**

* The dataset consists of 10 numerical and 8 categorical attributes. 
* The 'Revenue' attribute can be used as the class label. 
* 
* "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8. The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.



## Results

Our machine learning model achieved an accuracy of 88.8% in predicting online shopper intent. Detailed evaluation metrics and visualizations can be found in the project's Jupyter notebooks.

## Acknowledgments

We would like to acknowledge the support and guidance of our mentors and the contributions of the open-source community.

