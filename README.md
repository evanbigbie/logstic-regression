## logstic-regression

### This is from an undergrad ML course assignment. Instructions:

In this programming assignment, you will practice logistic regression. You will implement the logistic regression algorithm and apply it to two data sets.

In Part 1, you will build a logistic regression model to predict whether a student gets admitted into a university. Suppose that you are the administrator of a university department and you want to determine each applicant's chance of admission based on their results on two exams. You have historical data from previous applicants that you can use as a training set for logistic regression. For each training example, you have the applicant's scores on two exams and the admissions decision.
Your task is to build a logistic regression (i.e., binary classification) model that estimates an applicant's probability of admission based the scores from those two exams. 

1.1	Plot the training data

Please refer to the file “DataPlotting.ipynb” for how to plot training data. By visualizing the data, you can see that the data is linearly separable. Please attach the image of data visualization.

1.2	Implement the vectorized Sigmoid function
> def sigmoid(z):<br/><br/>
    """<br/>
    Compute the sigmoid of z<br/>

> Arguments:<br/>
z -- A scalar or numpy array of any size.<br/>

> Return:<br/>
s -- sigmoid(z)<br/><br/>
"""

> Start code here  
s =<br/>
End code here
    
> return s

1.3 What will happen if you don’t perform feature scaling?

1.4 Plotting the decision boundary
> After you have performed feature scaling, please run your algorithm to obtain the set of weights. Then, by referring to the file “DataPlotting.ipynb”, plot the decision boundary. Please attach the decision boundary image in this report.
