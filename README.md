# Diabetes Classification using Support Vector Machines (SVM)

## Description
This project aims to classify diabetes based on certain predictor variables using the Support Vector Machines (SVM) algorithm. The dataset used contains various features related to diabetes, and the SVM model is trained to predict whether a person is diabetic or not.

## Installation
To run this project, you need to have the following dependencies installed:
- numpy
- pandas
- scikit-learn

Additionally, download the dataset "diabetes.csv" and place it in the same directory as the code.

## Usage
1. Clone the repository or download the code files.

2. Install the required dependencies.If you have jupyter on your laptop,there is no need to install them as jupyter comes with this packagees installed


3. Run the code file, which contains the implementation of the SVM model for diabetes classification.

4. The dataset is loaded from the "diabetes.csv" file using pandas. The code then performs data preprocessing by standardizing the features.

5. The dataset is split into training and testing sets using a 80:20 ratio, with stratification to maintain the class distribution.

6. The SVM model with a linear kernel is trained on the training set.

7. The accuracy of the model is calculated on both the training and test data.

8. Finally, an example input data is provided, and the model predicts whether the person is diabetic or not.

## Results
The accuracy achieved on the training data is: 79%


The accuracy achieved on the test data is: 72%

## Input Format
The input data should be provided as a tuple of 8 values representing the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

For example: input_data = (6, 148, 72, 35, 0, 33.6, 0.627, 50)

## Output Format
The model will output a binary prediction indicating whether the person is diabetic or not.

## Additional Information
- The dataset used in this project is "diabetes.csv", which contains information about various factors related to diabetes.
- The project uses scikit-learn version
- This is a basic implementation of diabetes classification, and there is potential for further improvement by exploring different algorithms or tuning hyperparameters.

