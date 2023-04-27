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
Amongst these 3 models 'XGB' Boost regressor performed well with the R-square score of 81 on training and 78 on testing . which means that high proportion  of the variance is explained by independent feature. 

**Model Evaluation**
The evaluation of the model is done using R-squared metric.

**Take a quick Glance**

<img width="349" alt="image" src="https://user-images.githubusercontent.com/119112861/234952990-b99aac79-f2b6-42e1-8eaf-d206b191c785.png">

