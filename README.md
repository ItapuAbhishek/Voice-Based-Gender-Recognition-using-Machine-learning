# Voice-Based-Gender-Recognition-using-Machine-learning

*The significance of Gender identification in signal processing and multimedia interests me to pick this task of voice based Gender identification using Machine Learning.

*The dataset used for recognizing gender based on audio events is retrieved from kaggle.

*It is a large- scale collection of all frequency attributes of voice of both genders.The dataset includes 21 attributes and more than 3000 entries of sound clip information equally distributed of both genders.

*The problem falls under supervised learning as the system is trained by providing large number of labelled inputs for both genders.

*Also,it is a classification problem as the output is based on classifying into male or female.

*The goal is to compare outputs of various models and suggest the best model that can be used for gender recognition by voice.

*As a part of exploratory data analysis phase i took care of outliers using winsorize method and there are no missing values and duplicate values in the data

*Categorical and numerical features were one hot encoded and normalied respectively.All the analysis were performing using sklearn

*I ran Logistic Regression,Knearest neighbor,Support vector classifier,Random forest classifier,XGBOOST,XGBOOST gave the best accuracy scores among them.i proceeded with hyper tuning using gridsearch CV and was able to achieve 97% accuracy.

*Feature importance gives meanfun and IQR has got the most importance in classifying the gender among all the feature
