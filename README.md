## Rock and Mine Prediction Using Logistic Regression

This project is a machine learning application for predicting whether an object is a rock or a mine based on its sonar signal readings. The prediction is made using a Logistic Regression model
trained on the publicly available Sonar Dataset.

Overview
The goal of this project is to classify sonar data into two categories:

      R: Rock
      M: Mine

    Using logistic regression, the model processes 60 features representing sonar frequency intensities to make its predictions.

Dataset
The dataset used is the Sonar Dataset, which contains:

        208 rows (observations)
        60 columns (features representing sonar frequencies)

        A target column with values:
          R (Rock)
          M (Mine)

        The dataset is split into training and test sets using a 90-10
        ratio.

Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation
numpy for numerical operations
scikit-learn for model training, evaluation, and preprocessing

Model Performance
The model was evaluated using accuracy metrics:

         Training Accuracy: Evaluated on the training dataset.
         Test Accuracy: Evaluated on the test dataset.
