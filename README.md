# supervised-machine-learning-challenge


### Background

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

You will be using this data to create machine learning models to classify the risk level of given loans. Specifically, you will be comparing the Logistic Regression model and Random Forest Classifier.


#### Predict Model Performance

You will be creating and comparing two models on this data: a Logistic Regression, and a Random Forests Classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct!


# Prediction:

Between both models I believe the Random Forest Classifier has a higher chance of better performance

as its bootstrapping feature allows it to  classify outcomes based on a collection

of decision trees that the algorithm generates from the sample data.



#### Create, Fit and Compare Models

Create a Logistic Regression model, fit it to the training data that you created in the previous step. Then, determine the model's score by using the `score` function and the testing data from the previous step. Do the same for a Random Forest Classifier. You may choose any starting hyperparameters you like.

Review the scores of each model. Which model performed better? How does that compare to your prediction? Write down your results and thoughts in the designated markdown cell.



### Conclusion

*Which model performed better?

 When obtaining the scores on from both models initially, we can denote that both have very high scores.

 But when scaling the data, it is effortless to notice how the Logistic Regression model drops dramatically from 99% to 63% as this algorithm is highly sensitive to the range of data points.

 Whereas the Random forest Tree performed really well in both occassions, with the unscaled, and scaled data.

*How does that compare to your prediction?

Based on this, the result matches my prediction as the Random Forest classifier model provides a more robust and reliable prediction due to its bootstrapping feature.
