## Machine learning
## Default in telecom bills using python
### What the task and results are
We want to study the question whether a client will default or not next month, and figure out the most important variables among those 17 features.
There are 3 main parts in this project, including data preparation, data visualization in Python with Pandas, Matplotlib,
and Others, build 4 models and ensemble.

For the modeling part, We will use SVM, logistic regression, neural network, random forest and Extratree to build the model and tune hyper-parameters. (We would like to subsample the dataset since it takes too long to train)

Then, we get our ideal model for each algorithm. And we evaluate it by using ROC curve. Next, we would like to compare each of the best performing algorithms. And get the conclusions that if the performance of each algorithm might be statistically different.

Last, we combine the best performing algorithms into an ensemble. In our case, we use random forest and neural network to be ensemble classifer. Then, we evaluate the performance ensemble and individual algortihms.

Finally, based on our models, there are four main conclusions. 1. Based on accuracy, we can figure out that SVM and logistic regression have higher accuracy value. The higher, the better. 2. From all ROC curve, we find ensemble model are best model. Because area under the ROC curve is the highest (0.76). 3. The accuracy for test data of ensemble and SVM are the highest, which are 70.2% and 71.6%. 4. According to 95% confidence interval, we find that the performance of SVM and random forest are better.
