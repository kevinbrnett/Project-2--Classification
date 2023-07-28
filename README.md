# Classification Problem with Stroke Predictions

## Predicting Patients that are at Risk of Having a Stroke Using Various Factors 

Kevin Barnett

**Business Problem**:

Building a tool a primary care physician can use to accurately predict if a patient will have a stroke. Most importantly being able to rule out the possibility of the patient having a stroke.
 
## Data Source:

 Original Dataset: (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv)
 
 In this dataset there are 12 columns and 5110 rows.
 
 ## Data Dictionary:
 
 ![Data Dictionary](https://user-images.githubusercontent.com/103015330/232175076-4e742e3b-71b6-4a84-8033-72d5cc359f16.png)


## To Prepare the dataset, it was cleaned, and the following processes were performed:

## Exploratory Data Analysis:

**BMI vs. Age Status in Relation to Stroke**
![Plot 1](https://user-images.githubusercontent.com/103015330/232175081-e348034d-b3b0-441d-91c4-64d37daf48a5.png)




**BMI vs. Avg Blood Glucose in Relation to Stroke**
![Plot 2](https://user-images.githubusercontent.com/103015330/232175088-cf7751b4-e356-4e10-82b2-5b8b5b870348.png)



## Recommended Model Metrics:

- Random Forest Model with PCA:
  - Accuracy: 0.94
  - Recall: 1.00
  - Precision: 0.94
  - F1-Score: 0.97

## Final Recommendations:

-  The model I recommend putting into production is the Tuned Random Forest model with Principal Component Analysis. The business problem we are addressing is correctly predicting the patients at risk for stroke based on several factors. For this problem minimizing false negatives (type 2 errors) is most important. This model has false negatives ~3% of the time.


