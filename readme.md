# Data Preprocessing
- Data Merging (Grade1).ipynb handled the merging of data for grade 1 angina. The final dataset can be seen in dataset.csv. This dataset was not used in our final paper.
- Data Merging (Grade2).ipynb handled the merging of data for grade 1 angina. The final dataset can be seen in dataset_grade_2.csv. This was the main dataset was used in our final paper.

# Table 1 Code
- Table1 (Grade1).ipynb contains code for the table 1 values for grade 1 angina. This was not used in the final paper.
- Table1 (Grade2).ipynb contains code for the table 1 values for grade 2 angina. This was used in Table III in our final paper, describing the characteristics of grade 2 angina in our dataset versus each feature. Discussion for the table 1 values occured in section II - Data.
- Table1 Gum Disease.ipynb contains code for the table 1 values for Gum Disease. This was used in Table IV in our final paper, describing the characteristics of Gum Disease in our dataset versus each feature. Discussion for the table 1 values occured in section II - Data.

# Predictive Modeling
- Model Testing.ipynb contains code for the predictive modeling using all features (8 baseline features and 1 oral health feature - Gum disease). This includes preprocessing, train/validation/test split, SMOTE, hyperparameter tuning, and final evaluation on the test split. The evaluation metric values were used in Table I and Table II in our final paper. Discussion for predictive Modeling occured in section III - Methods (Predictive), IV - Hyperparameter Tuning, and V - Results (Predictive).
- Model Testing (no gum disease).ipynb contains code for predictive modeling. This includes preprocessing, train/validation/test split, SMOTE, hyperparameter tuning, and final evaluation on the test split. The evaluation metric values were used in Section III of the final paper. The results from this notebook are briefly mentioned in the conclusion subsection in section V - Results (Predictive).

# Causal Modeling
- Data Testing.ipynb conducts statistical testing between stratified samples (stratified on grade 2 angina or gum disease) and calculates P-values (using Welsh's T-Test) for each feature. This was used in Table III and Table IV in our final paper. Discussion for these P-values occured in section VI - Methods (Causal) and section VII - Results (Causal).
- Code for the p-values of categorical features (using Chi-squared test) are located Table1 (Grade2).ipynb and Table1 Gum Disease.ipynb. This was used in Table III and Table IV in our final paper. Discussion for these P-values occured in section VI - Methods (Causal) and section VII - Results (Causal).
- DAG Testing.ipynb tests the 4 different models used in the final paper and computes the odds ratios for various features to predict angina. Confidence intervals for the odds ratios are then calculated to see statistical significance. Discussion for these values occured in occured in section VI - Methods (Causal) and section VII - Results (Causal).