# Prediction-of-Diabetes-using-Classification-Algorithms

The principal aim of the study is to build a machine learning model that may foresee the probability of Diabetes inside the patients at its beginning phases with most extreme exactness reachable. As anticipating the likelihood of Diabetes fall inside the area of order issues with paired yields, we will use classification algorithms like Decision Tree, Support Vector Machine, and Naive Bayes during this exploration. After the modeling of the algorithms is finished, we may test and assess our outcomes based on its exhibition measures and with acceptable outcomes, would attempt to convey the machine learning model to be utilized in real-life cases.

We took dataset from kaggle which originally registered as the public dataset namely Pima Indians Diabetes Database (PIDD) which is sourced from UCI Machine Learning Repository. This Dataset consists of the medical details for 768 instances which are pregnant female patients.

1. Number of times pregnant
2. Plasma Glucose Concentration
3. Diastolic Blood Pressure (mm Hg)
4. Skin Fold Thickness (mm)
5. 2-Hour Serum Insulin (mu U/ml)
6. Body-Mass Index (BMI) (weight/(height)²)
7. Diabetes Pedigree Function
8. Class ‘0’ or ‘1’

As it is clearly visible that all three models works similar for this dataset. So the best suprvised Machine Learning algorithm is Support Vector Classifier (SVC) with the 82% accuracy and 0.76 Precision on test dataset in respective to other data models for this experiment.
The results we have obtained are within the range expected in the project proposal (75-80%), which is a good indicator as we have got results in the upper bound of expected range.

|Model |	Accurary % | Recall |	Precision	| F-Measure	| ROC |
|------|-------------|---------|----------|-----------|-----|
|**SVC**	|**0.82**	|**0.62**	|**0.76**	|**0.68	**|**0.77**|
|Decision Tree	|0.78	|0.45	|0.72	|0.55	|0.69|
|GaussianNB	|0.76	|0.62	|0.67	|0.64	|0.74|
|Random Forest	|0.81	|0.55	|0.74	|0.63	|0.73|
|XGBoost	|0.78	|0.55	|0.67	|0.60	|0.72|
