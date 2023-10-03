# Customer Term Deposit Prediction Model

## Problem Statement

The goal of this project is to develop a predictive model that can determine whether a customer will subscribe to a term deposit. The model will help identify potential customers who are more likely to subscribe to a term deposit, allowing the bank to target its marketing efforts more effectively and improve conversion rates.

## Dataset

The project uses a dataset that includes various features related to the customers, such as age, job, marital status, education, and previous marketing interactions. Additionally, it contains the target variable 'y', indicating whether the customer subscribed to a term deposit ('yes' or 'no').

The dataset can be found [Here](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing,).

## Methodology

1. **Data Preprocessing**: The dataset will be cleaned and preprocessed to handle missing values, encode categorical variables, and scale numerical features if necessary.

2. **Exploratory Data Analysis (EDA)**: We will perform EDA to gain insights into the data, visualize relationships, and identify patterns that can help in feature selection and engineering.

3. **Feature Engineering**: New features may be created, and existing features may be transformed to improve the model's predictive performance.

4. **Model Selection**: Various machine learning models, such as logistic regression, random forests, and Decision Trees, will be trained and evaluated to determine the best-performing model.

5. **Model Evaluation**: We will use appropriate metrics (accuracy, precision, recall, F1-score, etc.) to evaluate the model's performance. Cross-validation techniques will be employed to assess generalization.

6. **Hyperparameter Tuning**: Grid Search CV will be used to fine-tune the hyperparameters of the selected model.


## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/Yogendra19/customer-term-deposit-prediction.git

2. Open the Bank_Marketing.ipynb file and run all cells

3. Infrence the models at your own pleasure

4. Predictions can be done by providing valid attribute values in form of a Pandas Dataframe to any model one wishes to use


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
