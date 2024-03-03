Prediction of Survival of Patients in the ICU - Informatics Machine Learning Project

Situation (S):


In 2020, there were 33,356,853 hospital admissions in the United States. Quick assessment of a patient’s health upon admission is vital, especially in ICUs where chronic health data is often unavailable. To address this, we're analyzing data from the first 24 hours of admission, including blood tests, vital signs, and other factors like BMI and blood pH, to predict patient survival. Challenges include accurately predicting survival with limited initial data and the absence of chronic health information.

Task (T):


Our task is to analyze patient demographic data, medical history, and EHR records to predict illness severity and chances of survival using machine learning algorithms such as Random Forest Classifier and XGBoost Classifier. This analysis aims to identify key attributes indicating survival chances for patients with illnesses and facilitate faster diagnosis and treatment decisions. We aim to identify the major attributes contributing to survival.

Action (A):

Determined viable attributes for prediction.
Documented the total number of NA and blank values in each column.
Deleted columns with NA or blank values accounting for more than 35% of the total.
Utilized PivotTable to identify hospitals with the highest number of entries.
Conducted descriptive statistics before imputation, including mean, standard deviation, minimum, and maximum values.
Filled missing categorical variables with mode and missing numerical values with mean if normally distributed.
Differentiated distribution of columns with histograms for numerical and bar graphs for categorical columns.
Mapped categorical columns into numerical equivalents.
Utilized Spearman correlation to identify dependencies between columns.

Result(R):

Data cleaning reduced the dataset from 91,714 rows to 44,683 rows.
Application of machine learning algorithms (Random Forest Classifier and XGBoost Classifier) achieved significant accuracies.
Utilization of Synthetic Minority Oversampling Technique (SMOTE) improved accuracy further from 92 to 96%.
Identified major attributes contributing to patient survival, facilitating faster diagnosis and treatment decisions

 
 
