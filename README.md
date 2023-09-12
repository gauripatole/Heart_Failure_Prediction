# Heart_Failure_Prediction
Employing supervised machine learning algorithms to predict the accurate results with relevance to one's heart health. 

## Target Variable
Targeting 'HeartDisease' as the variable is justified due to its substantial healthcare impact, clinical relevance, preventive potential, quality data, ML challenge, and public health value.
 
## Machine Learning Algorithms
Machine learning algorithms play a crucial role in heart disease prediction by leveraging patterns and insights from medical data to provide accurate assessments of an individual's risk. The algorithms that we have employed for our project is as follows:
1. 	Decision Tree
2. 	Random Forest
3. 	Multilayer Perceptron Classifier
4. 	Support Vector Machine
5. 	Extra Tree
6. 	Logistic Regression
7. 	K-Nearest Neighbors
8. 	Gradient Boosting Classifier
9. 	Stacking Classifier 
 
Data Set Description
Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
1. 	Age: age of the patient [years]
2. 	Sex: sex of the patient [M: Male, F: Female]
3. 	ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4. 	RestingBP: resting blood pressure [mm Hg]
5. 	Cholesterol: serum cholesterol [mm/dl]
6. 	FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7. 	RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8. 	MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9. 	ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10.  Oldpeak: oldpeak = ST [Numeric value measured in depression]
11.  ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12.  HeartDisease: output class [1: heart disease, 0: Normal]
 
## Additional Analytics & Conclusion 
From the employed list of algorithms, Random Forest and additionally Stacking Classifier showed the top performance with the following performance metrics,
Random Forest – Train Accuracy:  92.52% | Test Accuracy: 85.814% | f1 Score: 86.64%
Stacking Classifier – Train Accuracy:  93.45% | Test Accuracy: 84.42% | f1 Score:  85.71%

 
## Scope of Future Work
Although the Random Forest and Stacking Classifier exhibited the top performance yet, we believe that by integrating ECG analytics we could hike the predictions for obtaining higher accuracies, further resulting in decisiveness in saving lives on humanitarian grounds.  
