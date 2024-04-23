# LoanApprovalPrediction

## Description
This study aims to identify key attributes that influence the approval or denial of loan applications and to evaluate the suitability of statistical models in predicting loan outcomes. Through bias analysis, the study will also determine if any gender or racial bias is captured using these models. The models will be compared to consider if some models capture larger magnitudes of bias than others, and why this might be. There are three main stages to the methodology: training models without the protected feature, training models with the protected feature and training models with additional simulated bias. At each stage, evaluation metrics will be calculated to compare performances of the models. Fairness metrics will be implemented to evaluate the presence of bias in different models and across various racial and gender demographics. Overall, the study demonstrated that highly accurate machine learning models can be created using the HMDA dataset to predict loan approvals. It was observed that a significant level of bias was found against Black applicants and a less prevalent bias was found against female loan applicants compared to male applicants. XGBoost and Light GBM captured the highest levels of bias across all explorations due to their capacity to explore more complex patterns in data.

## Files included
  * original_HMDA_dataset.csv
  * race_dataset.csv
  * sex_dataset.csv
  * sex_data_preprocessing.ipynb
  * race_data_preprocessing.ipynb
  * race_exploration.ipynb
  * sex_exploration.ipynb


