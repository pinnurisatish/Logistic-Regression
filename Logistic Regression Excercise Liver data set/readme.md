# Logistic-Regression
This repository contains all logistic regression models  
# Liver Patients - Logistic Regression
## Objective
Patients with liver disease have been continuously increasing because of excessive consumption of alcohol, inhale of harmful gases, intake of contaminated food, pickles and drugs. In an effort to reduce burden on doctors, the government has hired you as a data scientist to build a predictive machine learning that would give an indication whether a person would have liver problem or not. Now, as a data scientist, your goal is to build a logistic machine learning model that predicts whether a patient is healthy (non liver patient) or ill (liver patient) based on some clinical and demographic features (or input variables) listed in the 'Data Description' section.

## Dataset & Data Description
This data set contains liver patient records and non liver patient records collected from North East of Andhra Pradesh, India. The "Liver_Problem" column is the target variable used to divide groups into liver patient ( Liver_Problem == 1) or not ( Liver_Problem == 2).

```
Liver_Problem == 1, implies the individual is a liver patient
Liver_Problem == 2, implies the individual is not a liver patient
```
To load the dataset in your jupyter notebook, use the below command:

```
import pandas as pd
liver_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/liver_patient_data/indian_liver_patient_dataset.csv')
```

## Data Description:
<ol>
<li>Age of the patient
<li>Gender of the patient
<li>Total Bilirubin
<li>Direct Bilirubin
<li>Alkaline Phosphotase
<li>Alamine Aminotransferase
<li>Aspartate Aminotransferase
<li>Total Protiens
<li>Albumin
<li>Albumin and Globulin Ratio

"Liver_Problem" column is the target variable used to divide groups into liver patient (liver disease) or not (no disease).
Some of the data are slightly technical, you may refer online resources to learn more about them.
