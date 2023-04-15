# Classification Problem with Stroke Predictions

## Analyzing Various Risk Factors For Strokes To Predict Patients That Are At Risk For Strokes

Kevin Barnett

**Business Problem**:

Accurately predict if a patient is at risk for stroke based on several factors
 
## Data Source:

 Original Dataset: (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv)
 
 In this dataset there are 12 columns and 5110 rows.
 
 ## Data Dictionary:
 
 

## To Prepare the dataset, it was cleaned, and the following processes were performed:

## Exploratory Data Analysis:

**BMI vs. Age Status in Relation to Stroke**










## Recommended Model Metrics:

- Random Forest Model with PCA:
  - Accuracy: 0.94
  - Recall: 1.00
  - Precision: 0.94
  - F1-Score: 0.97

## Final Recommendations:

-  The model I recommend putting into production is the Tuned Random Forest model with Principal Component Analysis. The business problem we are addressing is correctly predicting the patients at risk for stroke based on several factors. For this problem minimizing false negatives (type 2 errors) is most important. This model has false negatives ~3% of the time.


