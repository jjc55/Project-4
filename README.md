# Project 4: Data Visualization and Machine Learning on a Diabetes Dataset

### Group Members: Juhi, Kesha, Lora, and Hima

### Description:
The goals of our project are to use data visualization techniques on a diabetes data set and to build a machine learning model that accurately predicts diabetes in patients using medical history and demographic information.

Using data from the World Bank, IDF Diabetes Atlas, and CDC, a Tableau dashboard was built to gain an overall understanding of diabetes globally and in the United States. Global prevalence, health expenditure, and demographic information relating to diabetes were investigated in this dashboard. 

DB browser in conjunction with SQLite were used to create a database for machine learning. Considering that the outcome is binary (i.e., patient either has diabetes or does not have diabetes), classification machine learning models, such as logistic regression, k-nearest neighbors, support vector classifier, and random forest classifier, were chosen. Then, accuracy scores were calculated using different methods, like StandardScaler, RandomOverSampler, and Synthetic Minority Oversampling Technique (SMOTE), to address the imbalanced data. The machine learning model with the highest accuracy score using Standard Scaler and SMOTE was the random forest classifier. As a results, we further evaluated the random forest algorithm with a classification report, confusion matrix, and feature importance plot.

### Team Member Responsiblities: 
1. Maintain READ.me: Juhi, Lora
2. Brainstorm about this project: Everyone
3. Build Tableau dashboard: Lora, Juhi
4. Clean ML data: Everyone
5. Perform Descriptive Analysis: Juhi
6. Create SQLite database: Hima
7. Address Imbalanced Data: Hima, Kesha
8. Train and Test the Machine Learning model: Hima, Kesha
9. Develop presentation: Everyone

### Files:
Tableau Dashboard: Global, National, and North Carolina

SQLite: sql.ipynp, diabetes_prediction_sqlite.csv, diabetes_prediction.db, sql.ipynb

Descriptive Analysis: diabetes_prediction_dataset.csv, Descriptive_analysis.ipynb, Histogram Images

Machine Learning Model: diabetes_prediction_dataset.csv, Final_ML.ipynb, ML Images

### Conclusion:
This project focused on data visualization and machine learning to better understand diabetes prevalence and how diabetes relates to demographic information and medical history. Findings show that there is a positive correlation between HbA1c and blood glucose levels and the risk of diabetes. The random forest algorithm demonstrated the highest level of accuracy compared to all other classification machine learning models. This random forest machine learning model presents as a solid foundation to be built upon to help healthcare professionals easily assess patients for risk of diabetes. 

### Links:
[Presentation](https://docs.google.com/presentation/d/1Fwp0ApqPC1A-W60X4_651ZGxSt-mDuQlyu1uq_cue68/edit?usp=sharing) 
<br> [ML Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) 
<br>[Tableau Dashboard](https://public.tableau.com/shared/NTWG8GRDJ?:display_count=n&:origin=viz_share_link)
