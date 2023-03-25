# Pima_Indians_Diabetes_IBM_SPSS_Modeler_and_Microsoft_Excel

- [Final IBM SPSS MODELER Project File](https://github.com/mahyarsab/Pima_Indians_Diabetes_IBM_SPSS_Modeler_and_Microsoft_Excel/blob/main/Mahyar_Sabouniaghdam_Final_Stream.str)

- [Final Microsoft Excel Project File](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fmahyarsab%2FPima_Indians_Diabetes_IBM_SPSS_Modeler_and_Microsoft_Excel%2Fmain%2F1.%2520Mahyar_Data_Analysis_using_Excel%2FHeart_Data_Final.xlsx&wdOrigin=BROWSELINK)


<img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*56ACHLa7d4YEXlfumEXkmg.jpeg">

## Microsoft Excel :

In the first part of the project, I analyzed the dataset, addressed missing values and generated visual charts by using the Microsoft Excel Data Analysis tool.

For cholestoral:

![Shot 0008](https://user-images.githubusercontent.com/122119114/224883838-d6edc915-6c93-49f6-987c-a0cb55284194.png)

Correlation Matrix (Pearson):

![Shot 0009](https://user-images.githubusercontent.com/122119114/224884299-62a449d0-ee46-4e61-9a47-3d0379fbc26a.png)

Normal Probability Plot after handling missing values:

![Shot 0012](https://user-images.githubusercontent.com/122119114/224884500-ad8a2087-3c8c-457e-b8cb-722f73074c04.png)


<img align=right src="https://jupiter-analytics.com/wp-content/uploads/2021/02/ibm_spss_modeler_logo.jpg">

## IBM SPSS Modeler :

In the second part, The objective of the project is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset bu using IBM SPSS Modeler. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.



The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

Pima Indians Diabetes Database can be downloaded from [here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).



The schema of the project in IBM SPSS Modeler:

![1  Schema of the project](https://user-images.githubusercontent.com/122119114/224886276-5a0b486c-bb25-4893-a74c-4ef0f6ed804e.jpg)

![2  Schema of the project 2](https://user-images.githubusercontent.com/122119114/224886279-68c9726b-7f8c-4fcb-ab0a-8ba0ebf75e74.jpg)

Test scores before performing anomaly detection algorithms:

![3  Before Performing Anomaly Detection Algorithms](https://user-images.githubusercontent.com/122119114/224886589-d6b08557-c8ee-4361-8904-3badca027d3f.jpg)

Test scores after performing anomaly detection algorithms:

![4  After Performing Anomaly Detection Algorithms](https://user-images.githubusercontent.com/122119114/224886669-7d214038-9d6e-4d53-aee3-2a4b7e17273b.jpg)

I ran different models like: C5.0, CART, Random Forest, Quest, Regression. I got the best test score with CHAID (Chi-squared Automatic Interaction Detection) model:

![5  Chi-Squared_Best_Model](https://user-images.githubusercontent.com/122119114/224886963-50f185fe-c242-4b75-8d38-db78bc13a548.jpg)

The final schema of the project:

![6  Final Schema](https://user-images.githubusercontent.com/122119114/224887006-68af31a4-4681-4c7f-b13b-69c9ad590704.jpg)

The hyperparameters of the model:



![7  Hyparameters](https://user-images.githubusercontent.com/122119114/224887098-579571ee-e0ca-4ebd-bad2-c72b5acbd1b8.jpg)

- Top 3 decisive features in predicting the target was Glucose, Age, BMI. 
