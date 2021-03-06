# Logistic-regression
To study the impact of various factors like BMI,BP etc, on diabetes,and using Machine Learning to predict whether or not a person has diabetes based on data about the patient such as blood pressure, BMI, age, and so on.The data was collected and made accessible as part of the Pima Indians Diabetes Database by the "National Institute of Diabetes and Digestive and Kidney Diseases." The selection of these cases from a wider database was subjected to many limitations. All of the patients here are girls aged 21 and over who are of Pima Indian ancestry (a subset of Native Americans).
![image](https://user-images.githubusercontent.com/63113653/148110272-35e80da1-6755-43de-8971-b49c6bdb610b.png)
Brighter colours in the heatmap above suggest higher correlation. Glucose levels, age, BMI, and the number of pregnancies all have strong correlations with the outcome variable, as shown in the table and heatmap. Take note of any associations between traits, such as age and pregnancies, or insulin and skin thickness.


![image](https://user-images.githubusercontent.com/63113653/148110785-1722674e-79f8-4dde-bc00-8f8d0e6870fd.png)


**The following conclusions can be drawn from the preceding diagram.******
The model is affected by glucose levels, BMI, pregnancies, and diabetes pedigree function, particularly glucose levels and BMI. It's encouraging to see our machine learning model corroborate what we've heard from doctors our entire livesBlood pressure has a negative impact on the prediction, implying that higher blood pressure is associated with the absence of diabetes. (It's also worth noting that blood pressure is more essential as a feature than age because blood pressure has a larger magnitude).Despite the fact that age was more closely related to the output variables than BMI (as we discovered during data exploration), the model favours BMI. This can occur for a variety of reasons, including the fact that the age-related association is also caught by another measure, whereas the information obtained by BMI is not.


![image](https://user-images.githubusercontent.com/63113653/148110444-e7b9a488-6a4c-4be8-a400-bd6b8cf60a96.png)
