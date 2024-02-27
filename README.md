# Heart-Disease-Prediction
![image](https://github.com/Godboleshubha/Heart-Disease-Prediction/assets/160310212/352f9ec9-04f3-4a3e-be93-803e2a239339)

The target is to identify whether the patient has heart disease or not.
# Introduction
* We will go through the entire data pipeline from data cleaning, preprocessing, staging, and modeling on a relative dataset. On our way, we will compare different machine learning models and try to measure their performance using various metrics. *

 # Dataset
Heart disease is the number one cause of death worldwide, so if you're looking to use data science for good you've come to the right place. To learn how to prevent heart disease we must first learn to reliably detect it.
Our dataset is from a study of heart disease that has been open to the public for many years. The study collects various measurements on patient health and cardiovascular statistics, and of course makes patient identities anonymous.

# Domain Analysis

Preventing heart disease is important. Good data-driven systems for predicting heart disease can improve the entire research and prevention process, making sure that more people can live healthy lives.

In the United States, the Centers for Disease Control and Prevention is a good resource for information about heart disease. According to their website:

About 610,000 people die of heart disease in the United States every year–that’s 1 in every 4 deaths.

Heart disease is the leading cause of death for both men and women. More than half of the deaths due to heart disease in 2009 were in men.

Coronary heart disease (CHD) is the most common type of heart disease, killing over 370,000 people annually.

Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.

# Dataset Description
**There are 14 columns in the dataset, where the patient_id column is a unique and random identifier. The remaining 13 features are described in the section below.

slope_of_peak_exercise_st_segment (type: int) : the slope of the peak exercise ST segment, an electrocardiography read out indicating quality of blood flow to the heart

thal (type: categorical): results of thallium stress test measuring blood flow to the heart, with possible values normal, fixed_defect, reversible_defect

resting_blood_pressure (type: int): resting blood pressure

chest_pain_type (type: int): chest pain type (4 values)

num_major_vessels (type: int): number of major vessels (0-3) colored by flourosopy

fasting_blood_sugar_gt_120_mg_per_dl (type: binary): fasting blood sugar > 120 mg/dl

resting_ekg_results (type: int): resting electrocardiographic results (values 0,1,2)

serum_cholesterol_mg_per_dl (type: int): serum cholestoral in mg/dl

oldpeak_eq_st_depression (type: float): oldpeak = ST depression induced by exercise relative to rest, a measure of abnormality in electrocardiograms

sex (type: binary): 0: female, 1: male

age (type: int): age in years

max_heart_rate_achieved (type: int): maximum heart rate achieved (beats per minute)

exercise_induced_angina (type: binary): exercise-induced chest pain (0: False, 1: True)  

# Conclusion

The models with the best performance for Heart Disease Prediction campaign are:
1.SVC:

- Offers consistently high accuracy with accuracy_score: 0.8800
- precision_score: 0.9500

- Maintains a decent balance between precision and recall.
2. GaussianNB:

- Achieves similar accuracy to SVC with accuracy_score: 0.8600

- Offers higher precision of recision_score: 0.9048 
