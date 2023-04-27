**Medical Premium Price Prediction**

This project aims to predict the medical premium price for an individual based on their medical history, demographics, and other relevant factors. The dataset used in this project contains information such as age, diabetes status, blood pressure problems, height, weight, known allergies, and premium price.


**DataSet Description** 

The data is provided in CSV format and includes the following features:

Age: The age of the patient in years.
Diabetes: Whether or not the patient has diabetes (0 = No, 1 = Yes).
BloodPressureProblems: Whether or not the patient has blood pressure problems (0 = No, 1 = Yes).
AnyTransplants: Whether or not the patient has received any organ transplants (0 = No, 1 = Yes).
AnyChronicDiseases: Whether or not the patient has any chronic diseases (0 = No, 1 = Yes).
Height: The height of the patient in centimeters.
Weight: The weight of the patient in kilograms.
KnownAllergies: Whether or not the patient has any known allergies (0 = No, 1 = Yes).
HistoryOfCancerInFamily: Whether or not the patient has a history of cancer in their family (0 = No, 1 = Yes).
NumberOfMajorSurgeries: The number of major surgeries the patient has undergone.
PremiumPrice: The premium price the patient is paying for their medical insurance.

**Model Building**

The models used in this project are Random Forest regressor, XGB Regressor, gradient boosting regressor. 
Amongst these 3 models 'XGB' Boost regressor performed well with the R-square score of 81% on training and 78% on testing . which means that high proportion  of the variance is explained by independent feature. 

**Insights Gained**
Age: Age is a key factor in determining medical premium as older individuals may require more healthcare services and are at higher risk for health problems.

Diabetes: Having diabetes can increase the risk for a variety of health problems, which can impact medical premiums.

BloodPressureProblems: Blood pressure problems can increase the risk for heart disease and other health problems, which can impact medical premiums.

AnyTransplants: Receiving organ transplants can be costly and can impact medical premiums.

AnyChronicDiseases: Having chronic diseases can increase the need for healthcare services and medications, which can impact medical premiums.

Height and weight: These factors can be used to calculate the patient's body mass index (BMI), which can be used to assess the risk for a variety of health problems that can impact medical premiums.

KnownAllergies: Having known allergies can impact the type and cost of medications and treatments required, which can impact medical premiums.

HistoryOfCancerInFamily: Having a history of cancer in the family can increase the risk for developing cancer, which can impact medical premiums.

NumberOfMajorSurgeries: The number of major surgeries a patient has undergone can be indicative of their overall health status and the need for healthcare services, which can impact medical premiums.

PremiumPrice: This is the dependent variable that the model is trying to predict based on the other features. Understanding how the other features impact premium prices can inform healthcare policies and interventions.

**Model Evaluation**

The evaluation of the model is done using R-squared metric.


**Take a quick Glance**

<img width="349" alt="image" src="https://user-images.githubusercontent.com/119112861/234952990-b99aac79-f2b6-42e1-8eaf-d206b191c785.png">

