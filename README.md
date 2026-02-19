# IBM-Course--Space-X-Falcon-9-First-Stage-Landing-Prediction
This lab introduces Predictive Analysis by building a machine learning pipeline to predict whether the first stage of the Falcon 9 rocket lands successfully.
The workflow includes several key steps. First, data preprocessing is performed to standardize the features. Then, the dataset is split into training and testing sets using train-test split.
Next, multiple machine learning models are trained, and Grid Search is applied to identify the optimal hyperparameters that maximize each algorithm’s performance. Using these best hyperparameter values, the models are evaluated to determine which one achieves the highest accuracy on the training data.
The algorithms tested in this lab are:

- Logistic Regression
- Support Vector Machines (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

Finally, the performance of the selected model is assessed by generating a confusion matrix, which provides insight into prediction accuracy and classification errors.
