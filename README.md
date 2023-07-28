# Classification Problem with Stroke Predictions

## Predicting Patients that are at Risk of Having a Stroke Using Various Factors 

Kevin Barnett

**Business Problem**:

Building a tool a primary care physician can use to accurately predict if a patient will have a stroke. Most importantly being able to rule out the possibility of the patient having a stroke.
 
## Data Source:

 Original Dataset: (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv)
 
 In this dataset there are 12 columns and 5110 rows.
 
 ## Data Dictionary:
 
 ![Data Dictionary](https://github.com/kevinbrnett/Stroke-Predictions-Classification/blob/main/images/Data%20Dictionary.png)

## To Prepare the dataset, it was cleaned, and the following processes were performed:

## Exploratory Data Analysis:

**Avg. Glucose Level vs. Age in Relation to Stroke**
![Plot 1](https://github.com/kevinbrnett/Stroke-Predictions-Classification/blob/main/images/Glucose_vs_Age_Plot.png)



**Age vs. Gender in Relation to Stroke**
![Plot 2](https://github.com/kevinbrnett/Stroke-Predictions-Classification/blob/main/images/Age_vs_Gender_Stroke.png)



**Age vs. Stroke in Relation to Work Type**
![Plot 3](https://github.com/kevinbrnett/Stroke-Predictions-Classification/blob/main/images/Age_vs_Stroke_Work.png)


## Recommended Model Metrics:

![Model](https://github.com/kevinbrnett/Stroke-Predictions-Classification/blob/main/images/Recommended_Model.png)

## Final Recommendations:

-  The model excels in identifying true negative cases with only 1.8% false negatives. The pitfall of the model is the high false positives (84%). It is recommended that a physician use the model to rule out the probability of having a stroke. In cases of the model predicting that a patient will have a stroke further testing should be conducted


