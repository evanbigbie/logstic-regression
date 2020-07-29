## logstic-regression

This is from an undergrad ML course assignment. Instructions:

> In this programming assignment, you will practice logistic regression. You will implement the logistic regression algorithm and apply it to two data sets.

> In Part 1, you will build a logistic regression model to predict whether a student gets admitted into a university. Suppose that you are the administrator of a university department and you want to determine each applicant's chance of admission based on their results on two exams. You have historical data from previous applicants that you can use as a training set for logistic regression. For each training example, you have the applicant's scores on two exams and the admissions decision.
Your task is to build a logistic regression (i.e., binary classification) model that estimates an applicant's probability of admission based the scores from those two exams. 

1.1	Plot the training data

Please refer to the file “DataPlotting.ipynb” for how to plot training data. By visualizing the data, you can see that the data is linearly separable. Please attach the image of data visualization.

	Implement the vectorized Sigmoid function
def sigmoid(z):
    """
    Compute the sigmoid of z

    Arguments:
    z -- A scalar or numpy array of any size.

    Return:
    s -- sigmoid(z)
    """

### START CODE HERE ###     
s = 1 / (1 + np.exp(-z))
    ### END CODE HERE ###
    
return s

	Cost function and gradient
E(W) =-1/m ∑_(i=1)^m▒〖(y^((i))  log⁡(h_W (x^((i) ) ))" + (1 –" y^((i)) ") "  log⁡〖(1-h_W (x^((i) ) )))〗 〗

∂/∂"wj"  E(W)  = 1/m(∑_(i=1)^m▒〖(h(x^((i) ))-y^i 〗)〖×xj〗^i)

	Learning the parameters based on file pa3-data1.csv
1.4.1. What will happen if you don’t perform feature scaling?

1.4.2. Plotting the decision boundary
After you have performed feature scaling, please run your algorithm to obtain the set of weights. Then, by referring to the file “DataPlotting.ipynb”, plot the decision boundary. Please attach the decision boundary image in this report.




########<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;my code between hash lines<br/>
########
