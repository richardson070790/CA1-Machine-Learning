
# Dataset Source and Description

## 1. Dataset Identification

**Dataset:** Student Performance (Portuguese language subject)  
**Author:** Paulo Cortez  
**Year:** 2008  
**Repository:** UCI Machine Learning Repository  

**Official source:** https://doi.org/10.24432/C5TG7T

## 2. Dataset Characteristics

The dataset contains 649 student records and 33 variables describing academic, demographic, family and social characteristics.

The data is stored in CSV format and uses a semicolon (`;`) as the field separator.

The original dataset includes information such as:
- Student age and gender
- Family background and parental education
- Study time and previous academic failures
- School support and extracurricular activities
- Absences and academic grades

## 3. Target Variable

The final grade variable (`G3`) was used to create a binary classification target:

- **Pass:** G3 >= 10
- **Fail:** G3 < 10

The resulting dataset contains 549 pass cases and 100 fail cases.

The previous grades (`G1` and `G2`) were excluded from the predictive features to reduce target leakage and investigate prediction without relying on earlier term grades.

## 4. Data Quality

The dataset contains:
- 649 observations
- 33 original columns
- No missing values
- No duplicate records

## 5. Project Usage

The dataset was used to train and evaluate two classification algorithms:

1. Logistic Regression
2. Random Forest

The project applies data preprocessing, stratified sampling, cross-validation and hyperparameter optimisation using GridSearchCV.

## 6. Reference

Cortez, P. (2008) *Student Performance*. UCI Machine Learning Repository.

Available at: https://doi.org/10.24432/C5TG7T
