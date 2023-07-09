# disaster-ship

Description:
This project uses a logistic regression model to predict passenger survival on a ship. The project utilizes historical data from a ship's voyage and applies machine learning techniques to estimate the likelihood of passenger survival based on various factors.

Key Features:

Loading and preprocessing the dataset: The code loads the dataset from a CSV file, removes irrelevant columns, and handles missing values, ensuring data quality and consistency.

Feature Selection: The relevant features, including 'Age,' 'Sex,' 'Pclass,' and 'Fare,' are selected as predictors, while the 'Survived' column serves as the target variable.

Splitting the dataset: The dataset is divided into training and testing sets using the train_test_split() function from the sklearn.model_selection module. This allows for independent training and evaluation of the model.

Logistic Regression Model: A logistic regression model is created using the LogisticRegression class from the sklearn.linear_model module. This model is suitable for binary classification problems like predicting passenger survival.

Training the Model: The logistic regression model is trained on the training set using the fit() method, enabling it to learn the underlying patterns and relationships in the data.

Prediction and Evaluation: The trained model is used to make predictions on the test set using the predict() method. The predicted values are then compared with the actual values using the accuracy_score() function from the sklearn.metrics module, providing an assessment of the model's accuracy.
