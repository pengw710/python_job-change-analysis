# python_job-change-analysis

Context and Content

A company active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses conducted by the company. Many people signup for the course. The company wants to forecast how many people will decide to work for the company and how many will look for a new job somewhere else once the training completes. 

This dataset is designed to understand the factors that lead a person to leave their current job for HR research. By model(s) that uses the existing credentials, demographics, experience data, I will predict the probability of a candidate looking for a new job or continue working for the company and interpret factors that affect their decisions.
The whole data divided into train and test. The target column is excluded in the test and saved in a separate file with the corresponding enrollee_id. 

Note:

•	The dataset is imbalanced.

•	Most features are categorical (Nominal, Ordinal, Binary), some with high cardinality.

•	Missing imputation can be a part of my pipeline as well.

Features

•	enrollee_id: Unique ID for the candidate

•	city: City code

•	city_ development _index: Development index of the city (scaled)

•	gender: Gender of the candidate

•	relevent_experience: Relevant experience of a candidate

•	enrolled_university: Type of University course enrolled if any

•	education_level: Education level of candidate

•	major_discipline: Education major discipline of the candidate

•	experience: Candidate total experience in years

•	company_size: No of employees in current employer's company

•	company_type: Type of current employer

•	lastnewjob: Difference in years between previous job and current job

•	training_hours: training hours completed

•	target: 0 – will not work for the company, 1 – will work for the company

Inspiration

•	Predict the probability that a candidate will work for the company

•	Interpret model(s) such a way that illustrates which features affect candidate decision

Hypothesises

1.	Candidates from a small company with high training hours will highly likely decide to work for the company.

2.	Candidates from a disadvanced city with high education level will highly likely decide to work for the company. 

3.	Male Candidates with fewer years of experience will less likely decide to change their current job (will not work for the company)
