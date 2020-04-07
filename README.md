# Heart_disease_Prediction
Heart disease prediction is the project in which using decision tree as classification algorithm we predict that the person will suffer from heart disease or not.
# Introduction
Heart diseases is a term covering any disorder of the heart. Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India.
# Problem Description :
A dataset is formed by taking into consideration some of the information of 1025 individuals. The problem is  based on the given information about each individual we have about 14 various describing  features and one target variable  and we have to predict that the person will suffer from heart disease or not. So we have use decision tree as classification algorithm.
# Dataset:
The dataset consists of 1025 individuals data. There are 14 columns in which 13 are describing features and 1 is target variable as binary variable  in  the dataset.
Age		:age in years
Sex		:(1 = male; 0 = female)
Cp		:chest pain type
Trestbps	:resting blood pressure (in mm Hg on admission to the hospital)
Chol		:serum cholestoral in mg/dl
Fbs		:(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
Restecg	:resting electrocardiographic results
Thalach	:maximum heart rate achieved
Exang	:exercise induced angina (1 = yes; 0 = no)
Oldpeak	:ST depression induced by exercise relative to rest
Slope	:the slope of the peak exercise ST segment
Ca		:number of major vessels (0-3) colored by flourosopy
Thal		:1 = normal; 2 = fixed defect; 3 = reversable defect
Target	:1 or 0

# Model Training and Prediction :
We can train our prediction model by analyzing existing data because we already know whether each patient has heart disease. This process is also known as supervision and learning. The trained model is then used to predict if users suffer from heart disease. The training and prediction process is described as  First, data is divided into two parts using component splitting. In this experiment, data is split based on a ratio of 70:30 for the training set and the prediction set
We have use decision tree as a classification algorithm for our problem statement to predict that the person will suffer from heart disease or not.
Our decision tree of max_depth= 2 is:

	 


Conclusion:
Accuarcy achived using decision tree model is 85%. And we have used confusion metrix to evaluate the accuracy of model also calcuted the precision,recall,F1 score for checking the accuracy of model.



