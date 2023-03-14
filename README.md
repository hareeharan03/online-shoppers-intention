# Online Shoppers Intention Machine Learning Model

This project aims to build a binary prediction machine learning model to predict the purchase intent of online shoppers, based on their online session attributes.

## Data Source

The data used for this project is from the Online Shoppers Intention Dataset from UCI's Machine Learning Library. The dataset consists of feature vectors belonging to 12,330 sessions. The dataset was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

The dataset contains 18 features (10 numerical and 8 categorical) and one target variable (Revenue) that indicates whether the session ended with a transaction or not.

## Features

The features used for this project are:

- Administrative: Number of pages visited by the visitor about account management
- Administrative_Duration: Total amount of time (in seconds) spent by the visitor on account management related pages
- Informational: Number of pages visited by the visitor about Web site information
- Informational_Duration: Total amount of time (in seconds) spent by the visitor on information related pages
- ProductRelated: Number of pages visited by visitor about product related pages
- ProductRelated_Duration: Total amount of time (in seconds) spent by the visitor on product related pages
- BounceRate: Average bounce rate value of the pages visited by the visitor
- ExitRate: Average exit rate value of the pages visited by the visitor
- PageValues: Average page value of the pages visited by the visitor
- SpecialDay: Closeness of the site visiting time to a special day
- Month: Month value of the visit date
- OperatingSystems: Operating system of the visitor
- Browser: Browser of the visitor
- Region: Geographic region from which the session has been originated
- TrafficType: Traffic source by which the visitor has arrived at the Web site
- VisitorType: Visitor type as ‘New Visitor’, ‘Returning Visitor’, and ‘Other’
- Weekend: Boolean value indicating whether the date of the visit is weekend
- Revenue: Class label indicating whether the visit ended with a transaction or not

## Machine Learning Models

The machine learning algorithms used for this project are logistic regression, support vector machine (SVM), and random forest. These algorithms are common and popular choices for classification problems that can handle both numerical and categorical features. They also have different strengths and weaknesses that can complement each other.

## Preprocessing

The preprocessing steps applied to the data are:

- Performed exploratory data analysis
- Splitting the data into training (80%) and testing (20%) sets using StratifiedShuffleSplit
- Performed feature selection to optimize the model
- Balanced the imbalanced dataset using SMOTE

## Evaluation Metrics

The performance metrics used to evaluate each model are:

- Accuracy: The proportion of correctly predicted instances
- Precision: The proportion of positive predictions that are true positives
- Recall: The proportion of true positives that are correctly predicted
- F1-score: The harmonic mean of precision and recall

## Installation and Usage

To run this project, you need to have Python 3 and some libraries installed on your machine. You can use pip or conda to install them.

The libraries required are:

- pandas
- numpy
- sklearn
- matplotlib

You can clone this repository or download it as a zip file. Then, navigate to the project folder and run the following command in your terminal:


