# Classification_data_tit
Analyse the data of titanic dataset where how many people survived based on their Age,Sex,Fare,Pclass. 
Algorithms used :- Logistic Regression, Decision Tree, Random Forest, KNN(KNearest Neighbours), Naive Bayes
Visualize the dataset using the seaborn library , used scatterplot, countplot.
Data wrangling : Since the data contains str values modified it using pd.get_dummies and dropped the null values in the data.
Assigned the values to X and Y , Split the data for training and Testing, Preprosssed the dataset using the Standard Scaler from Sklearn library.
Model Preparation: Created models and fit tranform to predict the output of the model.
Validation the models using Accurary score, Classification report, confusion matrix. 
Conclusion: Among all the above mentioned algorithms we got high accuracy level 79.9% in Decision Tree algorithm while using the Gini_index, while using the Enrotpy(information gain) we got almost similar score 79.4%.

Second most algorithm performed well is KNN we got accuracy level 78.4%

When comparing to other algorithms used we got the least accuracty 72% in Naive Bayes.
