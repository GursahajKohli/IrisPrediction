# IrisPrediction
This project deals with predicting various variants of Iris flower. 
This project analyzes the data, by importing Iris dataset, checking for missing values, checking dependency on independent variables, encoding variables, analyzing data, running various models on data and predicting the output with an accuracy of 98% with 5 models.

![Iris Flowers](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Machine+Learning+R/iris-machinelearning.png)

To check if the flower is belongig to the class of which Iris flower, we need to input various values.
We tested the data on various models made by:

1. Logistic Regression
2. KNN
3. SVM
4. Kernel SVM
5. Naive Bayes
6. Decision Tree Classifier
7. Random Forest Classifier

![Dependencies](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/Iris_dataset_scatterplot.svg/1200px-Iris_dataset_scatterplot.svg.png)

After the evaluation of models, we come to conclusion that we get an acuraccy of 98% and 100%. Since 100% means overfitting of the model, so we discard the Naive Bayes model, and any other model from the rest 6 models can be used for an acuraccy of 98%.
