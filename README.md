# stroke-prediction-xai

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

Dataset description:
1. id: Unique identifier
2. gender: Patient gender (Male, Female or Other)
3. age: Patient age
4. hypertension: 0 for no hypertension, 1 for hypertension
5. heart_disease: 0 for no heart disease, 1 for heart disease
6. ever_married: If the patient has experience on marriage (Yes or No)
7. work_type: Type of employment ("children" if the patient is a child, "govt_jov", "never_worked", "private", "self-employed")
8. residence_type: Patients' residence (Rural or urban)
9. avg_glucose_level: Average glucose level in blood
10. bmi: Body mass index
11. smoking_status: Patients' history of smoking ("formerly smoked", "never smoked", "smokes", "Unknown")
12. stroke: target value, 0 for no stroke and 1 for stroke
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient.

Dataset: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

For details regarding global and local explanation, refer to "Explaining shap model git.pdf" attached in this repo.
