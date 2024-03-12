**INTRODUCTION:**
The Heart Disease UCI dataset labels each patient whether they have heart disease or not according to features in it. I will try to create a model to predict whether a patient has 
heart disease or not by using logistic regression.

**About Dataset:** 
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, 
but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

Each row in dataset represents a patient. There are 14 attributes/features:
age - age in years
sex - (1 = male; 0 = female)
cp - chest pain type; ranges from 0 to 3 -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic
trestbps - resting blood pressure (in mm Hg on hospital admission; ranges from 94 to 200)
chol - serum cholestrol in mg/dl; ranges from 126 to 564
fbs - fasting blood sugar > 120 mg/dl; 1 = true; 0 = false
restecg - resting electrocardiographic results; ranges from 0 to 2
thalach - maximum heart rate achieved; ranges from 71 to 202
exang - exercise induced angina; 1 = yes and 0 = no
oldpeak - ST depression induced by exercise relative to rest; ranges from 0 to 6.2
slope - slope of the peak exercise ST segment; ranges from 0 to 2
ca - no. of major vessels (0-4) colored by flourosopy
thal - 3 = normal; 6 fixed defect; 7 = reversable defect
target - 1 = yes for heart disease and 0 = no for heart disease
