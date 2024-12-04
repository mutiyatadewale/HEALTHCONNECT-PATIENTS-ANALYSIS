# HEALTHCONNECT-PATIENTS-ANALYSIS
This is a healthcare dataset containing 55499 rows and 15 columns, each representing a unit of observation. The analysis is aimed to particularly identify most common diagnosis base on region, treatment outcomes success rate, geographical distribution of diseases base on specific medical condition and so on

Methodology
The Descriptive and statistical analysis were conducted using Panda on Jupyter notebook and visualizations were done on jupyter notebook and Tableau. 
The following steps were taken:

Importation of necessary libraries like Panda and dataset
Data cleaning and preprocessing (checking for missing values, removing duplicate values, converting to compatible data types. 

Exploratory analysis
Importation of necessary libraries like numpy , matplotlib, seaborn
Conducted univariate and bivariate analysis e.g. value count by one variable, value count by more than one variable.


Data visualization
Visualizations of the result of the exploratory analysis using specific chart size, and chart type e.g bar chart, axis labeling, legend, and chart title to give a clear and detailed visual representation

Statistical analysis
Importing libraries to perform predictive analysis; StandardScaler, LabelEncoder, train_test_split, LinearRegression, mean_squared_error, r2_score.
Dropped irrelevant columns and transformed categorical attributes into numerical attributes, defined independent variable X and dependent variable y, split data into train and test samples, defined regression model, applied model on training sample, made predictions on test samples, and evaluated model performance

Result
Insights from EDA 1: Arthritis is the most common medical condition at 9218, then Diabetes at 9216, and Hypertension at 9151. The number of medical conditions is close to one another with everything ranging from 9095 to 9218                                        

EDA 2 Insights Geographical distribution of disease by region. The Top 5 hospitals by medical conditions and hospitals standing in as region  Johnson PLC recorded 7 Arthritis, 9 Asthma, 7 cancer, 7 Diabetes, 6 hypertension and 2 obesity Smith LLC with 8 Arthritis 4 Asthma 5 cancer 11 Diabetes 11 hypertension and 5 obesity 11 Ltd Smith with Arthritis 9, 3 Asthma 6 cancer 4 Diabetes 6 hypertension 11 obesity Smith Group 6 Arthritis 2 Asthma 10 cancer 4 Diabetes 2 hypertension 10 obesity Smith Ltd with 7 Arthritis 5 Asthma 6 cancer 7 Diabetes 8 hypertension 7 obesity

EDA 3 Insight The normal, Abnormal, and Inconclusive report of each medication was recorded. The total Normal test result recorded was 18,517, the total abnormal test results was 18,267, and the total inclusive test result was 18,357. There is no large difference recorded. 

EDA 4 Insight
The medical condition table is based on the count of medical conditions by patient's age. The first row shows 2 arthritis recorded for age 13, 4 for age 14, 2 for age 15, 3 for age 16, and so on. it is the distribution of medical conditions and medical condition count by age.                                         

EDA 5 Insight This table shows each medical condition by gender. arthritis for females is 4642 and 4576 for males. Asthma is 4522 for females and 4584 for males. In total female patients were 27,726 and males 27,774.     

EDA 6 Insight
The chart generated the top 5 Doctors’ names based on the number of medications prescribed  
Micheal Smith prescribed 27 medications, Robert Smith and John Smith prescribed 22 each and 
James Smith and Michael Johnson prescribed 20 each                                                        

Predictive Analysis Report This 0.8117 RMSE suggests that the linear regression model is a good fit for the data, with about 81.57% of the variation in the dependent variable explained by the model. R2 score of -0.0003 is a low R-squared value, indicating that the model is not predicting the dependent variable well. this could be a result of overfitting the training data, resulting in a high Model_RLSE value. it could also be a result of data leakage between the training and the test sets and lastly, the RLSE model might not be the best model for the data.

