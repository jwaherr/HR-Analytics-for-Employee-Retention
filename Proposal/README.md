# Project Proposal 

This repo is one of the T5 Bootcamp requirements. 


# How can Data Science support the HR department in a company?

Data Science can help the HR department by predicting the retention of an employee within a company whether the employee will leave or stay in the company. 
This project aims to use the previous employee's data who have worked in the company to find a pattern that will help to predict the retention in the form ( "Yes" = 1, "No" = 0)


## Dataset

To achieve the goal of this study the dataset **HR Analytics for employee rentension** will be used. 

The dataset contains 14,999 records, each record has 10 features. The most important feature of this project is the class label (left) which is indicate if the employee has left the company or not.
This dataset can be found at [Kaggle](https://www.kaggle.com/pankeshpatel/hrcommasep).

This dataset contains: 

•	satisfaction_level -> An employee satisfaction level at a job between 0 and 1
•	last_evaluation -> Last evaluation rating of an employee between 0 and 1
•	number_project ->Number of projects an employee was involved in
•	average_montly_hours -> Average number of hours in a month that an employee spent at the office
•	time_spend_company -> Number of years employee spent in the company in years 
•	work_accident-> Indicate if an accident happened during employee stay or not (0 - no accident  1 - accident occurred)
•	promotion_last_5years ->
•	department -> Department an employee belongs to
•	salary -> Salary ranges (high - medium - low)
•	left (class label) ->0 indicates employee stays in the company, 1 indicates - employee left the company


The dataset is available as the ```.csv``` file. A sample of data is shown in the following table:
<table width="100%">
 <tr>
  <th>id</th><th>satisfaction_level</th><th>last_evaluation</th><th>number_project</th><th>average_montly_hours</th><th>time_spend_company</th><th>work_accident</th><th>promotion_last_5years</th><th>department</th><th>salary</th><th>left</th>
 </tr>
 <tr>
  <th>0.38</th><th>0.53</th><th>2</th><th>157</th><th>3</th><th>0</th><th>0</th><th>sales</th><th>low</th><th>1</th>
 </tr>
</table>


## Questions and Contribution

•	How likely is an employee to leave their company or stay in the company?
•	What is the main reason that causes employees to leave? 
•	How many factors influence an employee to leave their current job? 
•	Which is the department that has the most risk of leaving?
•	Can this model help to form a better workplace culture by identifying the factors that cause an employee to leave? 


## Tools

Some tools will be used to achieve the goal of this study, such as  ```Scikit-Learn, Seaborn, Matplotlib, Pandas, NumPy ``` for exploring the data and training the model. 
The work will be done utilizing the Jupyter notebook to predict the prospects of future and present employees.


## **Plan**: 
• Explore the data and come up with EDA phases then use a model to fit the data.  
• **NOTE:** the used features may be increased or changed and the model as well. 
