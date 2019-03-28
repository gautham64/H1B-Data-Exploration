
Dataset is available in the location,
https://www.kaggle.com/jonamjar/h1b-data-set-2017/downloads/H-1B_Disclosure_Data_FY17.csv/1

# Introduction

The purpose of this Data Analysis Report is to predict the case status of H1B Visa Applications. It provides in-depth breakdown of all the relevant components to be considered certified for an H1B visa application. This report will include the description of the dataset and its variables, the data exploration and visualization process, data cleaning and preprocessing, the data mining model, and a discussion of the business insights and possible future improvements of this project.

# Description of the Data

The original dataset contains 52 variables with approximately 625,000 entries covering the period from 2012 to 2017. Some variables are grouped together for the ease of management. Among all variables, majority are categorical, only the wage group is numerical.
The case group variables include unique CASE_ID, CASE_STATUS, DECISION_DATE, and VISA_CLASS. This group indicates the last significant event or decision that was made on each case and the date the last significant action was taken. The VISA_CLASS variable has four different subcategories which specifies the countries for H1B applications.
The next group of variables describes employers. The covered details include the name, the full address, and the contact information of the employer as well as the start and end date of the employee’s employment.
The job group collects data about each applicant’s current job, which includes the job title, the occupation that the job is linked to, and the industry of the employer. These details are essential as they are needed to determine if the application meets the temporary labor condition as determined by the Department of Labor.

# Purpose of the Project

The purpose of the project is to use this H1B dataset to inform the class about certain trends in the data that relate to applicants who hope to obtain this visa type. Many visualizations and analytical explorations in this project can provide a better understanding of the H1B application for multiple audiences ranging from college students and foreign workers (current or prospective) in the United States to U.S. employers. The end goal of this project is to build a classification model to predict the possible case status of a submitted H1B application.
