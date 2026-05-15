# Zyfra-Gold-Mining
An integrated project of data preparation, EDA, model development and training
### Introduction
Today, I will be presenting a data-driven project focused on the gold mining recovery process at Zyfra. The primary objective of this work is to use the provided data on extraction and purification to simulate and better understand the recovery process. Building on this foundation, we aim to design a prototype machine learning model capable of improving efficiency within heavy industry operations.

Our approach is structured in three key stages:

- Data Preparation – cleaning, aligning, and validating the raw process data.

- Exploratory Data Analysis – identifying patterns, anomalies, and critical features that influence recovery outcomes.

- Model Development and Training – building and evaluating predictive models to optimize production and reduce unprofitable process parameters.

By combining data analysis with machine learning, this project seeks not only to capture the dynamics of the recovery process but also to support decision-making for more efficient, profitable, and sustainable operations.

## Work Flow

1. **Import Libraries**

   * Import Python libraries needed for data analysis, visualization, preprocessing, machine learning, and model evaluation.

2. **Data Exploration**

   * Load each CSV dataset
   * Review dataset structure, columns, and data types

3. **Data Validation and Analysis**

   * Validate recovery calculations using MAE comparisons
   * Compare calculated and actual recovery values
   * Analyze missing features between training and test datasets
   * Identify and categorize missing parameters, targets, and later process features

4. **Data Cleaning**

   * Identify and compare missing values
   * Identify duplicate records

5. **Data Preprocessing**

   * Convert date columns
   * Sort datasets by date and time

6. **Data Evaluation and Analysis**

   * Identify and compare processing stages
   * Create visualizations of findings
   * Build a pipeline to identify and remove anomalies

7. **Model Development**

   * Calculate the final sMAPE metric

8. **Model Training**

   * Train Linear Regression model
   * Train Random Forest Regressor model
   * Train Gradient Boosting Regressor model

9. **Model Evaluation**

   * Select the best-performing model
   * Compare model performance using sMAPE on the testing set

10. **Conclusion**

* Summarize findings, model results, and insights
