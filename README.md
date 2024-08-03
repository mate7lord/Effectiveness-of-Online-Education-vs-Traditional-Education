# Effectiveness of Online Education vs Traditional Education

## Project Overview

This project aims to analyze and compare the effectiveness of online education versus traditional classroom education. The analysis is based on the "Students Performance in Exams" dataset, which includes information on student scores in three subjects: Math, Reading, and Writing. 

## Objective

The primary objectives of this project are:
1. To identify the factors that influence the effectiveness of online and traditional education.
2. To compare student performance across both educational methods.

## Dataset

The dataset used for this analysis is "Students Performance in Exams," sourced from Kaggle. It includes the following variables:
- Gender
- Race
- Parental Education
- Lunch type
- Test Preparation
- Scores in Math, Reading, and Writing

You can find the dataset [here](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams).

## Methodology

1. **Data Collection**: Load and examine the dataset.
2. **Data Cleaning and Preprocessing**: Handle missing values (if any) and encode categorical variables.
3. **Exploratory Data Analysis (EDA)**: 
   - Analyze the distribution of scores.
   - Use box plots and correlation matrices to understand relationships between variables.
4. **Statistical Analysis**: Compute mean and standard deviation for each subject.
5. **Model Building**:
   - Linear Regression
   - Random Forest
   - Feature Importance using Random Forest
   - Hyperparameter Tuning using GridSearchCV
6. **Model Evaluation**: Evaluate models using MAE and RMSE.
7. **Results and Discussion**: Summarize findings and discuss implications.
8. **Conclusion and Future Work**: Provide key takeaways and suggest future research directions.

## Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using the following command:
```sh
pip install pandas matplotlib seaborn scikit-learn
