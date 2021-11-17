# HR-Analytics-for-Employee-Retention
Jawaher Alhuthayfi

## Abstract 
This project aimed to build a machine learning model with high prediction accuracy to help the HR department in a company to know how likely an employee leaves their company or stays in the company, and recognize the factors that lead a person to leave their current job. The data used in this project is provided by Kaggle, the data of the company has multiple records with different parameters and a two-class classification label that indicates whether the employee left the company or not. A machine learning model will be built to train the dataset to predict whether a certain employee will leave the company or not by employing Logistic Regression using Python (scikit-learn). Also, visualizing the results using seaborn and matplotlib.

## Design
This project is intended for the T5 Data Science BootCamp requirements. Data provided by Kaggle has been used in this project. It consists of company records of different parameters for each employee (such as satisfaction level, salary, number of promotions, department, etc.). Using machine learning algorithms to train from the dataset can help the HR department to classify who’s at risk of leaving and assist them to pinpoint the main reason. Which is beneficial to avoid the time and financial cost of replacing employees

## Data
The dataset is provided in .csv format. It contains 14,999 records, each record has 10 features. The most important feature of this project is the class label (left) which is indicate if the employee has left the company or not.

## Algorithms

***Feature Engineering***

1- Preformed data binning for only two columns by grouping rating data values into specific bins or groups according to this criteria:

• Low —> ( 0.0, 0.49 )

• Mid —> ( 0.5, 0.69 )  

• High — ( 0.7, 1.0 )

2- Preformed dummy variable conversion for 4 categorical columns where it converts one categorical column to a data frame with dummy variables.

3- Preformed Feature Scaling for all features to be equally in weigh. 

***Models***

Logistic Regression, Decision Tree, and KNN were utilized in this project.


***Model Evaluation and Selection***

Logistic Regression, Decision Tree, and KNN were utilized to classify employees.The Decision Tree performed the best. The model was trained with 11,991 records and was split into 70%-30% for train and testing. The official metric was the F1 score of the model, where the model tested on the accuracy, precision, recall, and F1 score. The result of used model:   

• F1: 98% for 0 (Stayed), 89% for 1 (Left) 

• Precision: 98% for 0 (Stayed), 88% for 1 (Left) 

• Recall: 97% for 0 (Stayed), 90% for 1 (Left) 

• Accuracy: 96%



## Tools
- Numpy and Pandas for data manipulation
- Scikit-learn for modeling and feature scaling
- Matplotlib and Seaborn for plotting

