To predict Diabetes in Women using Machine Learning models

Summary
Diabetes in women is very common these days. It would be good to find out the factors influencing the condition, and have the awareness to correct or control those factors if possible.

Question
How can Machine learning models be used to predict the occurrence of Diabetes in women

Data source
https://www.kaggle.com/code/chanchal24/diabetes-dataset-eda-prediction-with-7-models/input?select=diabetes.csv
The dataset has 9 attributes of 768 volunteers researched. The feature characteristics are as follows

Outcome - (have diabetes or not)
Age 
Blood Pressure
Glucose
BMI
Insulin
Number of pregnancies
Skin Thickness
Diabetes Pedigree (Probability in family)


Methods used

Data preprocessing
. Clean the data (missing values)
. Remove irrelevant features , converting categorical to numerical values

Exploring ML models
. Logistic Regression
. Decision Trees
. K-Nearest neighbors
. Random Forest
. Support Vector Machines

Model Evaluation
Analyze and compare the performance of each model using accuracy score

Results

Among the 6 models analyzed, Random Forest Classifier model performed better than the others with the highest accuracy score. 
After looking at the feature importance from Random Forest model, the main features influencing the outcome are found to be the insulin level, Age and Glucose levels. 

