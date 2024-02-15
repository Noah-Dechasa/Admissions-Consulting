# Admissions Data Analysis Project
Project Overview
This project involves a comprehensive analysis of admissions data for the academic year 2021-22. Utilizing logistic regression, we aim to identify factors that significantly influence a student's likelihood to apply, based on initial inquiries, demographic information, and other relevant predictors.

# Objective
The primary goal is to understand what drives potential applicants to submit their applications, with a focus on:

The impact of inquiries on application submission.
The influence of the applicant's state, Sophomore contact, household income, and distance to Wooster.
Identifying trends and actionable insights to enhance future recruitment strategies.
#Methodology
We employed logistic regression models to examine the relationship between various predictors and the likelihood of application submission. This involved:

# Initial data cleaning and preprocessing.
Exploratory data analysis to visualize the distribution of applicants by state and other categories.
Fitting multiple logistic regression models to pinpoint significant predictors.
Using odds ratios to interpret the effect size of significant predictors.
# Key Findings
Inquiry status emerged as a critical factor, with those making inquiries vastly more likely to apply.
Specific states showed varying likelihoods of application submission, indicating the importance of tailored recruitment strategies.
Sophomore contact, while initially hypothesized to increase application likelihood, showed a nuanced impact, suggesting the need for a review of outreach timing and messaging.
# Repository Structure
Data/: Contains the Admissions_data_2021_22.xlsx file with the raw admissions data.
Scripts/: R scripts for data loading, preprocessing, analysis, and visualization.
data_preprocessing.R: Script for data cleaning and initial processing.
data_analysis.R: Contains logistic regression models and exploratory data analysis visualizations.
model_evaluation.R: Script for comparing models based on AIC and BIC, and extracting odds ratios for interpretation.
Figures/: Generated plots and visualizations from the analysis.
