# Analysis-of-Categorical-Data-Project-2

This project applies **multinomial logistic regression** to predict student academic program type using socioeconomic and academic performance variables. The analysis was conducted in **R** as part of a statistical modeling project.

## Project Overview

The goal of this project is to examine how predictors such as **socioeconomic status (SES)**, **math scores**, and **science scores** influence a student's likelihood of belonging to one of three educational program categories:

- **Academic**
- **General**
- **Vocational**

Because the response variable contains more than two categories, a **multinomial logistic regression model** was used.

## Methods Used

The project includes:

- Data exploration and descriptive statistics
- Data visualizations
- Contingency table analysis
- Chi-square test of independence
- Mosaic plot analysis
- Multinomial logistic regression modeling
- Generalized logit equations
- Coefficient interpretation
- Model comparison using likelihood ratio testing
- Classification table and prediction accuracy evaluation

## Key Findings

- **Socioeconomic status (SES)** was found to be the strongest predictor of program type.
- **Math and science scores** showed relatively weak predictive effects.
- The multinomial model was statistically significant overall, though classification performance was limited due to class imbalance.

## Technologies Used

- **R**
- **R Markdown**
- Packages:
  - `nnet`
  - `ggplot2`
  - `dplyr`
  - `caret`
