Sonar Object Classification

This project demonstrates a binary classification task using Logistic Regression. The model is trained on a dataset of sonar signals to classify objects as either rocks or mines.

Dataset

The dataset used for this project is the Sonar Dataset, which contains signals obtained by bouncing sonar waves off various objects. Each instance has 60 numerical features representing energy values of sonar signals, followed by a label (R for rocks, M for mines).

Requirements

To run this project, you need the following dependencies:

Python 3.x
NumPy
Pandas
scikit-learn
Installation

Clone the repository:

  git clone https://github.com/your_username/sonar-object-classification.git
  cd sonar-object-classification

Install the required Python packages:

  pip install -r requirements.txt

Ensure that the sonar data.csv file is in the project directory.

Usage

Training the Model

The script reads the sonar dataset, preprocesses it, and trains a Logistic Regression model.

Run the script:

   python sonar_classification.py

Input Prediction

The script allows you to test the trained model with custom input data. Examples are provided in the code:

# Example input data
  input_data = (0.0079, 0.0086, 0.0055, ..., 0.0059, 0.0032)

The model will output whether the object is a Rock or a Mine based on the provided input.

Outputs

Training Accuracy: The accuracy of the model on the training dataset.

Test Accuracy: The accuracy of the model on the test dataset.

Predictions: Classification results for custom input data.

Example output:

  Accuracy of training data: 0.85
  Accuracy of test data: 0.80
  Prediction: ['M']
  The object found is a Mine

File Structure

sonar_classification.py: The main script for training and testing the model.
sonar data.csv: The dataset file (ensure it is in the same directory).
README.md: Documentation for the project.

License

This project is open-source and available under the MIT License.

Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

Acknowledgments

The Sonar Dataset is publicly available from the UCI Machine Learning Repository
