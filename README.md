# LoanApprovalPrediction

## Description
This study aims to identify key attributes that influence the approval or denial of loan applications and to evaluate the suitability of statistical models for predicting loan outcomes. There are three main stages to the methodology: training models without the protected feature, training models with the protected feature and training models with additional simulated bias. At each stage, evaluation metrics will be calculated to compare performances of the models. Fairness metrics will be implemented to evaluate the presence of bias in different models and across various racial and gender demographics. Overall, the study demonstrated that highly accurate machine learning models can be created using the HMDA dataset to predict loan approvals.

## Files included
  * features_description.pdf -  this documentation is provided by the Consumer Financial Protection Bureau
  * race_dataset.csv.zip - processed dataset used for training models for race exploration
  * sex_dataset.csv.zip - processed dataset used for training models for sex exploration
  * added_race_bias.csv.zip - dataset with additional race-related bias
  * added_sex_bias.csv.zip - dataset with additional sex-related bias
  * sex_data_preprocessing.ipynb - preprocessing code for dataset for sex bias exploration 
  * race_data_preprocessing.ipynb - preprocessing code for dataset for race bias exploration 
  * raceincluded.ipynb - code for models for training included race
  * sexincluded.ipynb - code for models for training included sex
  * racenotincluded.ipynb - code for models for training not including race attribute
  * sexnotincluded.ipynb - code for models for training not including sex attribute
  * raceaddedbias.ipynb - code for models for training with additional race-related bias
  * sexaddedbias.ipynb - code for models for training with additional sex-related bias
  * raceevaluationresults.xlsx - Excel spreadsheet containing results from race exploration
  * sexevaluationresults.xlsx - Excel spreadsheet containing results from sex exploration

## Orginal HMDA dataset:
Due to the large size of the original HMDA dataset, it is not able to be uploaded to Github. However, the original dataset can be accessed through this link: 
https://s3.amazonaws.com/cfpb-hmda-public/prod/dynamic-data/2022/2022_lar.zip

