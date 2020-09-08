# diabetes-prediction-using-logistic-regression

 We’ll be using Machine Learning to predict whether a person has diabetes or not, based on information about the patient such as blood pressure, body mass index (BMI), age, etc.
 
 What is logistic regression ?
 
 If you recall Linear Regression, it is used to determine the value of a continuous dependent variable. Logistic Regression is generally used for classification purposes. Unlike 
 Linear Regression, the dependent variable can take a limited number of values only i.e, the dependent variable is categorical. When the number of possible outcomes is only two it
 is called Binary Logistic Regression.
 
 Model :-
 
Output = 0 or 1
Hypothesis => Z = WX + B
hΘ(x) = sigmoid (Z)

Cost Function
Like Linear Regression, we will define a cost function for our model and the objective will be to minimize the cost.
The cost function for a single training example can be given by:
