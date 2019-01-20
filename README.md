## Salary Prediction

### Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Algorithms](#algorithms)
* [Approach](#approach)

### Introduction
Ever wondered how most of the job search websites give an estimate of the salary for the jobs posted on their website. They rely mostly on the salaries reported by the people for similar jobs.This process can further be fine tuned by implementing text analytics to accurately predict the salaries of the jobs based on the job descriptions.  
Here in this project, we classified the salaries into two categories(high and low) and classified the jobs using job description.

[Salary prediction based on job description.ipynb] (https://github.com/akhilesh-reddy/Salary-classification-based-on-job-description/blob/master/Salary%20prediction%20based%20on%20job%20description.ipynb) file contains the code for the analysis

[Salary prediction based on job description.ipynb](https://github.com/akhilesh-reddy/Salary-classification-based-on-job-description/blob/master/Salary%20prediction%20based%20on%20job%20description.ipynb) file has the code for the analysis

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
