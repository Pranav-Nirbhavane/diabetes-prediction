# **☝ Predicting if someone has diabetes using machine learning**

This notebook looks into using various Python based machine learning and data science libraries in as attempt to build a machine learning model capable of predicting whether or not someone has diabetes based on their medical attributes.

We are going to take the following approach:

1. Problem defination
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

# **1. Problem Defination**

In a statement,
> Given clinical parameters about a patient, can we predict whether or not they have diabetes?

# **2. Data**

The original data came from kaggle.
https://www.kaggle.com/datasets/asinow/diabetes-dataset/data

# **3. Evaluation**
> If we can reach 95% accuracy at predicting whether or not a patient has diabetes during the proof of concept, we will pursue the project.

# **4. Feature**

This dataset contains **9,538** medical records related to diabetes diagnosis and risk factors. It includes various health parameters, lifestyle habits, and genetic predispositions that contribute to diabetes risk. The data is structured with realistic distributions, making it valuable for medical research, statistical analysis, and machine learning applications.

1. **Age**: The age of the individual (18-90 years).

2. **Pregnancies**: Number of times the patient has been pregnant.

3. **BMI (Body Mass Index)**: A measure of body fat based on height and weight (kg/m²).

4. **Glucose**: Blood glucose concentration (mg/dL), a key diabetes indicator.

5. **BloodPressure**: Systolic blood pressure (mmHg), higher levels may indicate hypertension.

6. **HbA1c**: Hemoglobin A1c level (%), representing average blood sugar over months.

7. **LDL (Low-Density Lipoprotein)**: "Bad" cholesterol level (mg/dL).

8. **HDL (High-Density Lipoprotein)**: "Good" cholesterol level (mg/dL).

8. **Triglycerides**: Fat levels in the blood (mg/dL), high values increase diabetes risk.

10. **WaistCircumference**: Waist measurement (cm), an indicator of central obesity.

11. **HipCircumference**: Hip measurement (cm), used to calculate WHR.

12. **WHR (Waist-to-Hip Ratio)**: Waist circumference divided by hip circumference.

13. **FamilyHistory**: Indicates if the individual has a family history of diabetes (1 = Yes, 0 = No).

14. **DietType**: Dietary habits (0 = Unbalanced, 1 = Balanced, 2 = Vegan/Vegetarian).

15. **Hypertension**: Presence of high blood pressure (1 = Yes, 0 = No).

16. **MedicationUse**: Indicates if the individual is taking medication (1 = Yes, 0 = No).

17. **Outcome**: Diabetes diagnosis result (1 = Diabetes, 0 = No Diabetes).

# **5. Exploratory Data Analysis**

**5.1 Outcome Distribution [BAR]**

![image](https://github.com/user-attachments/assets/b984d7d9-a7a3-4991-a8b9-10ae1a80167b)

**5.2 Outcome Distribution [PIE]**

![image](https://github.com/user-attachments/assets/96b13643-0532-44a9-a5ef-6ab9a08bd9b9)

**5.3 Age VS Hb1Ac levels**

![image](https://github.com/user-attachments/assets/082fa3fb-ee66-450c-b799-594415b3c4d0)

**5.4 Glucose VS BMI Chart**

![image](https://github.com/user-attachments/assets/8d30b771-9eef-4a19-a87a-9b79a0ebe3bc)

**5.5 Glucose levels of Diabetic and Non-Diabetic**

![image](https://github.com/user-attachments/assets/8072734e-2a74-411a-a19b-bc2b21efbd12)

**5.6 Diabetes Frequency with Different Dietypes**

![image](https://github.com/user-attachments/assets/2113c8e0-02a8-4a33-8ef3-6af9d8638d00)

**5.7 Correlation Matrix**

![image](https://github.com/user-attachments/assets/2147e700-1a05-44fc-9fa6-63a790885387)

# **6. Modelling Metrics**

**6.1 Comparing different model accuracy**

![image](https://github.com/user-attachments/assets/88055d53-21e5-46bd-80fa-7aeddcf9e4da)

**6.2 ROC CurveDisplay**

![image](https://github.com/user-attachments/assets/2b99823f-36a3-4f43-8668-757308e5ce1c)

**6.3 Confusion Matrix**

![image](https://github.com/user-attachments/assets/58e82736-362a-476b-9ee0-6d8a879e7627)

# **7. Feature Importance**

![image](https://github.com/user-attachments/assets/f39da0ee-0ea8-4159-a2b0-1b1099d74ca8)
