In the field of machine learning and data analysis, Naive Bayesian and Perceptron algorithms
have proven to be highly effective in various applications. They provide us with powerful tools
to make predictions, classify data, and gain insights from complex datasets. In this task, we aim
to classify the wheat seed dataset using these two different methods. The dataset consists of
various features related to seed properties, and the goal is to classify the type of seed based on
these features. We discard any irrelevant features that do not contribute significantly to the
classification task. The Perceptron is a binary classifier that learns weights to create predictions,
in contrast to the Naive Bayesian technique, which assumes that the features are conditionally
independent given the class labels.


Results:
The accuracy of the Naive Bayesian method on the test set(15%) is 100%. I would like to
mention that when the test data is increased then the accuracy is decreased. On the other hand,
the accuracy of the Perceptron on the test set is 33.33%. Here, one important thing is to note that
perceptron works well on binary classification but the dataset that I have chosen has a multiclass
value. For this, I have to reshape the data and that affects the performance of the perceptron.
