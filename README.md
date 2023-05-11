# Phase_3_Project
***Problem Statement***

The business problem in this scenario is to identify the factors that contribute to customer churn in the telecom industry. The telecom company wants to develop a machine learning model that can predict the likelihood of customer churn based on various customer characteristics and usage patterns. The goal is to use this model to identify customers who are at high risk of churning and take proactive measures to retain them. By reducing customer churn, the company can improve customer satisfaction, increase revenue, and gain a competitive advantage in the market.

Data Source of this project: https://www.kaggle.com/becksddf/churn-in-telecoms-dataset

Presentation of this project : 

***Objective(s) of this Project:***

Based on the given dataset, the following objectives will be defined:

*Main Objective* 

Develop a machine learning model to predict the churn score based on usage pattern.

*Specific Objectives*

1. Identify the factors that contribute to customer churn.

2. Evaluate the effectiveness of retention strategies.

3. Give appropriate recommendations to assist in minimizing the churn rate.

The company - who is our stakeholder may be interested in asking the following questions that we aim to answer with our model:

1. What are the most common reasons for customer churn?
2. How likely are the customers likely to churn, based on their usage patterns and customer characteristics?
3. How can the company prevent its customers from churning?
4. What retention strategies have been most effective in reducing customer churn?

***Stakeholder:***

The Telecom company that provided the dataset is the primary stakeholder. They are interested in identifying the reasons behind customer churn and developing strategies to reduce churn and increase customer retention as well as increase their revenue.

***Perfomance Metrics:***

A combination of metrics such as accuracy ,precision, recall ,F1-score AND ROC- AUC  can be used to evaluate the performance of the model and ensure that it meets the business requirements and goals of the telecom company.

***Target Variable***

Churn: if the customer has churned = true else = False.

#### *Data Science Process Used:*
CRISP-DM stands for Cross-Industry Standard Process for Data Mining. It is a widely used process model for data mining that provides a structured approach to data analysis projects. The CRISP-DM process consists of six main stages:

1. Business Understanding:
In this stage, the objectives and requirements of the project were defined. This includes understanding the problem to be solved, the objectives of the project, identifed the key stakeholders and their expectations,The perfomance metrics that will be used to measure perfomance of the model and Traget variable. constraints of the project. 

2. Data Understanding:
In this stage, the data is loaded and examined to understand its structure, quality, and suitability for analysis. The main goal is to identify potential data quality issues and assess the accuracy, completeness, and consistency of the data.Also did exploratory data analyis.

3. Data Preparation:
In this stage, data is transformed, cleaned, and preprocessed to make it suitable for analysis. This included;
  * Data Type conversion.
  * Removing outliers.
  * Normalizing our dataset.
  * Dealing with multicolinearity.
  * Spliting the data.
  
4. Modeling:
In this stage, statistical and machine learning models are developed using the preprocessed data.Three models were created ;
  * Decision Tree Model.
  * Logistic Model.
  * Normalizing our dataset.
At each model stage the models were tuned ,evaluated and visualized and a comparision of the metrics done before and after tuning.  

5. Evaluation:
In this stage, the models developed are evaluated to determine their effectiveness in solving the problem. This includes testing the model on a holdout data set and comparing the results with the actual outcomes.This was accommodated in the modelling stage.

6. Deployment:
In this stage, the model  with the best perfomance was Decision Tree having the best f1 score at 0.64.

### *Conclusion*

We can conclude a number of things from the previous visuals shown:

* The account length w of 90 days and above has more likelyhood of churning

* The area code 415 records

* An increase of charges leads to customers churning.

### *Recommendations*

What can the company do to retain customers and what retention strategies can be adopted:

* Customers who use SyriaTel should be highly encouraged to get onto the international plan.

* A value add on should be given to customers when they start approaching 90 days and above of being members.

* Customer-centric Approach: provide personalized and tailored services that enhance the customer experience.

* Quality Assurance: maintain high-quality customer service across all touchpoints.

* By conducting a thorough analysis, evaluating costs, considering customer value, assessing revenue impacts and exploring value-added services the company can strategically lower call charges while main.

### *RETENTION STRATEGIES :*

A couple of retention strategies SyriaTel can adopt to maintain its customers:

* Personalized Offers: Tailored offers and discounts to individual customers based on their usage patterns, preferences, and loyalty.

* Proactive Customer Support: to include regular check-ins, timely responses to queries, and proactive troubleshooting.

* Value-added Services that enhance the overall customer experience.

* Provide special retention offers to customers who express their intention to switch to another provider.

* Regularly review and adjust pricing strategies to remain competitive in the market.




