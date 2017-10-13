## Instructions for using this notebook ##

This fold contains three notebooks, including two machine learning algorithms, decision tree and Naive Bayes and one text preprocessing notebook called text featurization.

Also,we provide three classification datasets that could be applied to either of the two ML algorithms. ["iris.data"](https://archive.ics.uci.edu/ml/datasets/iris) has four attributes with continuous values describing three different iris species.


For decision tree, the algorithm used here is called CART (classification and regression tree), which can take both discrete and continuous values as the input. For illustration purpose, we provided two datasets, iris.data and lenses.txt. All the variables in iris.data are continuous values and all the variables in lenses.txt are discrete values. When discrete string values are inputted, the notebook will print the codebook for each continuous variable.

For Naive Bayes, we provide a spam dataset named SMSSpamCollection.txt to help you learn how machine learning algorithms solve real-world problems. With the help of three different Naive Bayes algorithms, we can build models to tell if an unseen SMS is spam or ham. testset_SMS.txt is the testset. Please open this file and copy and paste the text in it to Jupyter notebook when you want to test prediction function.
