Final report of models:

    Random forests are much simpler to train for a practitioner; it’s easier to find a good model. The complexity of a random forest grows with the number of trees in the forest, and the number of training samples we have. In SVMs, we typically need to do a fair amount of parameter tuning, and the computational cost grows linearly with the number of classes as well.

    Even without controlling GridSearchCV params, the Random Forest Model was much more effective and capable in classifying candidate exoplanets.

    Also, between the two models SVM and LogisticRegression, they didn't have any significant difference between them for this data, even hyperparameters tuning didn't help the differentiate the models. We can say SVM model performs sligtly better. Which means that the Random forests classier is the best model.
