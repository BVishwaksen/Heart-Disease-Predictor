# Heart-Disease-Predictor
A machine learning based system that is used to predict the presence of heart disease based on patient's symptoms.
## Table of Contents
[Introduction](#Introduction)
[Requirements](#Requirements)
[How-To-Use](#How-To-Use)
[Dataset](#Dataset)
[Technical-Details](#Technical-Details)
[Algorithm](#Algorithm)
[Lisence](#Lisence)
### Introduction
The danger of heart diseases is increasing because of unhealthy life style and stress in day to day life.The cardiologists use many tests to conclude whether a person has a heart disease or not.This may be error prone because the accuracy of conclusion mainly depends on doctor's experience. So the objective of this project is to design an intelligent system that can predict the presence of heart problem based on the person's medical reports.
### Requirements
Python 3.5 or above version with numpy,pandas,matplotlib,scikit-learn,seaborn and pickle packages.
Jupyter lab/Jupyter notebook
No specific hardware requirements and runs on any operating system
### How-To-Use
After downloading and extracting the repository open it in jupyter notebook.Then open the `Heart-Disease-Predictor.ipynb` file.In that file change the values of `person_reports` variable.
The order of the values are `age,sex,cp,trestbps,chol,fbs,restecg,thalach,exang,oldpeak,slope,ca and thal` and then run all the cells.The presence of heart disease is displayed as the output of the last cell.

### Dataset
The dataset used in this project is Heart-Disease dataset from UCI Machine Learning repository
The dataset can be downloaded from <https://www.kaggle.com/ronitf/heart-disease-uci>
### Technical-Details
##### Dataset Details
The dataset contains 14 attributes and 303 instances.
The column details are
age (in years)
sex (1 = male; 0 = female)
cp (chest pain type)
trestbpsresting blood pressure (in mm Hg on admission to the hospital)
cholserum (cholestoral in mg/dl)
fbs (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
restecgresting (electrocardiographic results)
thalachmaximum (heart rate achieved)
exangexercise induced angina (1 = yes; 0 = no)
oldpeakST (depression induced by exercise relative to rest)
slopethe (slope of the peak exercise ST segment)
canumber of major vessels (0-3) colored by flourosopy
tha (l3 = normal; 6 = fixed defect; 7 = reversable defect)
target (1=presence or 0=absence)
##### Files Organization
The project is implemented in python in Jupyter Notebook environment.It mainly contains two parts.The `heart-disease-trainer.ipynb` is for training the data and the `heart-disease-predictor.ipynb` is to load the trained data and to predict results.The `heartdisease_model.sav` is the model that is saved.The `Heart.csv` is the file that contains the dataset in comma seperated values format.
### Algorithm
The Heart Disease Prediction is a type of classification problem.As here there are only two types of target values this comes under `binomial classification`.
The algorithm used in this is `Logistic Regression`.More details about this algorithm can be found at <https://en.wikipedia.org/wiki/Logistic_regression>
### Lisence
This is a public repository and you can be used in research,commercial and non-commercial applications without any restrictions.

