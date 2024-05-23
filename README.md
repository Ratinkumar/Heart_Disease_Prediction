# Heart_Disease_Prediction
Predicting HEART DISEASE using ML. This Project uses various python-based ML and Data Science libraries in an attempt to build a ML model capable of predicting whether or not someone has HEART DISEASE based on their MEDICAL ATTRIBUTES

We are going to take following approach -

problem definition
data
evaluation
features
modelling
experimentation
# 1. Problem Statement

Given clinical parameters about a patient , can we predict whether or not they have heart disease

# 2. Data

The original data came from Cleavland data from UCI machine learning repo https://archive.ics.uci.edu/ml/datasets/heart+Disease

that is also on Kaggle https://www.kaggle.com/datasets/ratinkr/heart-disease

# 3. Evaluation

if we can reach 95% accuracy at predicting whether or not a patient has heart disease during proof of concept , we will pursue the project

# 4. Features

create data dictionary

age: age in years

sex: sex (1 = male; 0 = female)

cp: chest pain type -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic

trestbps: resting blood pressure (in mm Hg on admission to the hospital)

chol: serum cholestoral in mg/dl

fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

restecg: resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

thalach: maximum heart rate achieved

exang: exercise induced angina (1 = yes; 0 = no)

oldpeak = ST depression induced by exercise relative to rest

slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping

ca: number of major vessels (0-3) colored by flourosopy

thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

num: diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing

# Preparing the tools

we are going to use pandas,numpy,matplotlib for data analysis and manipulation
