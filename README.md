# Project Description
The objective is to optimize the accuracy of prediction of death of patients in a ICU. Data is patient-related characteristics such as vital signs (i.e., HeartRate, SysBP,etc) diagnosis and comorbidities, and personnel data (i.e., age, ethnicity, etc). For such, minimal preprocessing and feature engineering is performed. Prediction techniques used are KNN Classifier and SVM classifiers (SVC). Each of these models are fine tuned doing grid search over different parameters and introducing K-best feature selection. Accuracy Scores in out of sample prediction on in-class Kaggle Competition are 0.91 for KNN and 0.90 for SVC.

# Data
Data used comes from the MIMIC project (https://mimic.physionet.org/). A large, freely-available database comprising deidentified health-related data associated with over forty thousand patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.
