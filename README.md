# Multiclass Classifier on MNIST
Applying Multiclass Classification on MNIST data.

[Notebook](https://github.com/sambuddharay/multiclass-classifier-on-mnist/blob/main/MNIST_classification.ipynb)

# Motivation
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.

In this project, will implement multiclass classification using Logistic Regression with -
1. SGD i.e. SGDClassifier(loss='log')
2. solvers i.e. LogisticRegression(loss='lbfgs')

The SGDClassifier implements a plain stochastic gradient descent learning routine which supports different loss functions and penalties for classification. SGD (stochastic gradient descent) is an optimisation technique used to train models. SGD has been successfully applied to large-scale and sparse machine learning problems often encountered in text classification and natural language processing. Given that the data is sparse, the classifiers in this module easily scale to problems with more than 10^5 training examples and more than 10^5 features.



# References
[https://github.com/faizanxmulla/machine-learning-practice](https://github.com/faizanxmulla/machine-learning-practice)\
[https://scikit-learn.org/stable/modules/sgd.html](https://scikit-learn.org/stable/modules/sgd.html)\
[https://michael-fuchs-python.netlify.app/2019/11/11/introduction-to-sgd-classifier](https://michael-fuchs-python.netlify.app/2019/11/11/introduction-to-sgd-classifier/)