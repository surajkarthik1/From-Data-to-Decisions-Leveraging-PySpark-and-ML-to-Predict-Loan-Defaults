# From-Data-to-Decisions-Leveraging-PySpark-and-ML-to-Predict-Loan-Defaults

Project Overview:
This project utilizes historical loan application data from the Machine Hack Data Repository to predict loan defaults. By employing various machine learning models, the analysis provides insights that help financial institutions mitigate risks associated with loan defaults.

Dataset Description:
The dataset consists of 96,376 loan application records, each detailed with 35 features like loan amount, funded amount, interest rates, and other financial attributes that are pivotal for predicting the likelihood of a loan default.

Data Processing and Analysis:

Data preprocessing was executed using Apache PySpark, which is adept at handling large datasets:

Missing Values: Filled missing entries to maintain the integrity and accuracy of the dataset.

Feature Standardization: Categorical labels were standardized to maintain consistency across the dataset, crucial for accurate model input.

Data Transformation: Utilized PySpark for data transformation and normalization, ensuring the data is suitable for processing by machine learning algorithms.

Exploratory Data Analysis (EDA)

Key Insights: The EDA phase answered crucial questions regarding the distribution of loan amounts, interest rates, and borrower reliability, helping identify patterns and trends.

Visualization: Created visual representations to understand relationships between different variables and their impact on loan default probabilities.

Feature Engineering
Dataset Balancing: Implemented SMOTE to overcome class imbalance in the target variable, crucial for unbiased model performance.

Encoding and Scaling: Encoded categorical variables and normalized data ranges to prepare data for effective model training.

Model Development and Evaluation
Evaluated various models to identify the best performer in predicting loan defaults:

1. Logistic Regression
2. Naive Bayes
3. Decision Trees
4. Random Forest
5. XGBoost: Chosen as the best model due to its high accuracy of 88%.

Models were assessed using metrics like accuracy, precision, recall, F1-score, and AUC-ROC, ensuring the predictions are both reliable and applicable.

Project Conclusions
The analysis successfully addressed several questions like:

* What are the key predictors of loan default?
* How does borrower behavior impact loan repayment?
* What impact do loan terms and interest rates have on the likelihood of default?
  
The conclusion drawn from the project is that certain features such as borrower's credit score, loan amount, and past financial behavior are critical in predicting defaults. The XGBoost model, with its robust handling of various data types and complex relationships, proved to be highly effective in forecasting defaults, which can help financial institutions in crafting better loan approval criteria to minimize risks.
