# classification-challenge
Showcasing Pandas, Python, and Sklearn, the challenge gathers data about spam. It separates the data into train and test datasets and scales them. Instances of the Logistic Regression and Random Forest Classifier models are created and fitted to the train/test data. The models and testing data are used to create predictions. Model and accuracy scores are calculated to determine the better performing model.

## Installing
The repo is public and can be cloned at:

https://github.com/col-mustang/classification-challenge

## Program
##### Prerequisites
The starter files consist of the following files:  
`spam_detector.ipynb`

#### Step 1:
Navigate to the "spam_detector.ipynb" file in GitHub repo. The output for each panel can be viewed in the "Preview" panel.

#### _Alternatively,_

#### Step 1:
Clone the repository.

#### Step 2:
In terminal, activate your conda environment and type conda scikit-learn.

#### Step 3:
If the library is installed in your conda environment, the terminal will output the package name and version number. If installed, skip to Step 5. If not installed, go to Step 4.

#### Step 4:
pip install -U scikit-learn

#### Step 5:
Open "spam_detector.ipynb"

#### Step 6:
Run all panels.

## Technologies Used 
- Python
- Pandas
- scikit-learn

## Built With
- Visual Studio Code
- ChatGPT

## Requirements
-To receive all points, your Jupyter notebook file must have all of the following:

- Split the Data into Training and Testing Sets (30 points)
- There is a prediction about which model you expect to do better. (5 points)

- The labels set (y) is created from the “spam” column. (5 points)

- The features DataFrame (X) is created from the remaining columns. (5 points)

- The value_counts function is used to check the balance of the labels variable (y). (5 points)

- The data is correctly split into training and testing datasets by using train_test_split. (10 points)

-Scale the Features (20 points)
- An instance of StandardScaler is created. (5 points)

- The Standard Scaler instance is fit with the training data. (5 points)

- The training features DataFrame is scaled using the transform function. (5 points)

- The testing features DataFrame is scaled using the transform function. (5 points)

-Create a Logistic Regression Model (20 points)
- A logistic regression model is created with a random_state of 1. (5 points)

- The logistic regression model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

- Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

- The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

-Create a Random Forest Model (20 points)
- A random forest model is created with a random_state of 1. (5 points)

- The random forest model is fitted to the scaled training data (X_train_scaled and y_train). (5 points)

- Predictions are made for the testing data labels by using the testing feature data (X_test_scaled) and the fitted model, and saved to a variable. (5 points)

- The model’s performance is evaluated by calculating the accuracy score of the model with the accuracy_score function. (5 points)

-Evaluate the Models (10 points)
- The following questions are answered accurately:

  - Which model performed better? (5 points)

  - How does that compare to your prediction? (5 points)

## Contributing
edX Boot Camps LLC
## Authors
edX Boot Camps - _Initial work_

Geoff McDaniel - _Final work_