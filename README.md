## Salary Prediction
Here in this project, Job descriptions have been used to predict the expected salary. This problem has been simplified into a classification problem by splitting the salaries into high and low salaries. 
Bernoulli and Multinomial Naive Bayes, Random forest and XGBoost have been used for this exercise after performing the pre-processing steps like removing stop words, removing pucntuations, lemmatizing etc. The jupyter notebook contains a detailed of the process that has been followed

### Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Algorithms](#algorithms)
* [Approach](#approach)

### Introduction
Ever wondered how most of the job search websites give an estimate of the salary for the jobs posted on their website. They rely mostly on the salaries reported by the people for similar jobs.This process can further be fine tuned by implementing text analytics to accurately predict the salaries of the jobs based on the job descriptions.  
Here in this project, we classified the salaries into two categories(high and low) and classified the jobs using job description.
	
### Technologies
Project is created with:
* Python 3.6.5   
**Datasource**
* salary description dataset from Kaggle

### Algorithms
* Naive Bayes Bernoulli
* Naive Bayes Multinomial
* Random Forest
* XGboost

### Approach:
1. Data pre-processing
	  * Removal of punctuations and noise from job descriptions
	  * Removal of stop words
	  * Lemmatization
2. Classification using just categorical variables other than job description
3. Classification using Job description using different algorithms
4. Conclusion
