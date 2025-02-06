# **Titanic Survival Prediction**  
This repository contains a machine learning model to predict the survival of passengers aboard the Titanic. The model uses passenger data (such as age, gender, class, etc.) to estimate the likelihood of survival.

## **Overview**  
The Titanic disaster of 1912 is a well-documented event. This project leverages machine learning techniques to analyze passenger data and predict whether a person would have survived the tragedy. The project is a classic introductory example in machine learning, providing insights into data preprocessing, feature engineering, and classification models.

- *PassengerId*: Unique ID for each passenger  
- *Pclass*: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- *Name*: Passenger's name  
- *Sex*: Gender of the passenger  
- *Age*: Age of the passenger  
- *SibSp*: Number of siblings/spouses aboard the Titanic  
- *Parch*: Number of parents/children aboard the Titanic  
- *Ticket*: Ticket number  
- *Fare*: Ticket fare  
- *Cabin*: Cabin number  
- *Embarked*: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)  

## Data Preprocessing  
The dataset had missing values, which were handled as follows:  
- Missing values in *Age* were filled with the mean age.  
- Missing values in *Embarked* were filled with the mode.  

## Data Analysis  
Exploratory data analysis (EDA) was conducted to understand the dataset better. The following visualizations were created:  

1. *Pie Charts*  
   - Distribution of male vs. female passengers.  
   - Proportion of survived vs. non-survived passengers.  
   - Distribution of passengers by port of embarkation.  

2. *Count Plots*  
   - Comparison of survived vs. non-survived passengers based on gender.  
     - Insight: A higher proportion of females survived, even though there were more male passengers.  
   - Passenger survival based on ticket class (*Pclass*).  
     - Insight: First-class passengers had higher survival rates than second and third-class passengers.  

3. *Correlation Analysis*  
   - Correlations between various features were analyzed to identify relationships.

## Model Development  
The model used for prediction is *Logistic Regression*.  
- *Training Accuracy*: 80.75%  
- *Testing Accuracy*: 78.21%  

## Key Insights  
- Female passengers had a significantly higher survival rate compared to males.
- Passengers in First Class were given priority during rescue efforts, leading to higher survival rates.
- Logistic Regression provided good accuracy, making it a reliable model for this dataset.


##### **Getting Started** 
Clone the repo and install dependencies.
