# Comparative_Study_ML_Classification

A Paper on Comparative Study of various Machine Learning Classification Models on Thyroid Disease Dataset 

Index:
- Thyroid_Disease_Classification.ipynb: Code used for implementing the Study
- Thyroid_Disease_Classification.pdf: Research Paper

## Abstract
We have glands in our entire body, and they are distributed according to the requirement to release any substances that are required by our body. Thyroid is a vital gland for our body which helps in many functions. Men, women, teenagers, elderly, and infants alike can be affected by the thyroid disease.

A person would be more likely to come across with this disease if they happen to have a history of thyroid disease in the family. In terms of ease of diagnosis, relative visibility and the ease of diagnosis, thyroid diseases are very much different. Early diagnosis and treatment remain the key factors. Different types of thyroid states are: Hyperthyroid, Hypothyroid, Euthyroid- sick, and Euthyroid (negative). 

In our journey through the project, we collected and worked on the data and then we used normalization followed by data splitting. Then, we trained several classification models: Logistic Regression,Naive Bayes,Decision Tree,Random
Forest,SVM (Support Vector Machine),Gradient Boost,Adaboost and Bagging. 

Later we did hyperparameter tuning to evaluate models. We then ended the project with visual metrics. The first time we got the accuracy of 74.54% and later on after modifying the algorithm, we got an improved accuracy of 87.34%. This final result was obtained using the Decision Tree Classifier after Hyperparameter tuning.

After training the data and testing it with all the models mentioned above, the final result we obtained was from DecisionTreeClassifier(maxfeatures=’auto’, maxleafnodes=2, randomstate=1). This model gave us the highest accuracy i.e. of
87.34491315136476%.
