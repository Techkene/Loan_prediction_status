# Loan Prediction Status Model
This project focuses on predicting loan status using a credit risk dataset. The goal is to assess the creditworthiness of applicants and classify their loan approval status based on key features in the dataset.

### Overview
The project involves building and evaluating machine learning models to predict loan approval. Various steps, including feature selection, data scaling, and evaluation with classification metrics, were carried out to improve model performance.

### Table of Contents
1. Features
2. Technologies Used
3. Data Preprocessing
4. Modeling and Evaluation
5. Results
6. How to Use
### Features

The dataset is composed by 32581 rows (observations) and 12 columns (variables).

- person_age: is the age of the person at the time of the loan.

- person_income: is the yearly income of the person at the time of the loan.

- person_home_ownership: is the type of ownership of the home.

- person_emp_length: is the amount of time in years that person is employed.

- loan_intent: is the aim of the loan.

- loan_grade: is a classification system that involves assigning a quality score to a loan based on a borrower's credit history, quality of the 
collateral, and the likelihood of repayment of the principal and interest.

- loan_amnt: is the dimension of the loan taken.

- loan_int_rate: is the interest paid for the loan.

- loan_status: is a dummy variable where 1 is default, 0 is not default.

- loan_percent_income: is the ratio between the loan taken and the annual income.

- cb_person_default_on_file: answers whether the person has defaulted before.

- cb_person_cred_hist_length: represents the number of years of personal history since the first loan taken from that person.

### Technologies Used
Python

**Libraries:**

Pandas, NumPy (for data manipulation)

Scikit-learn (for modeling and evaluation)

Matplotlib/Seaborn (for data visualization)

### Data Preprocessing
**Feature Selection:** Selected features that significantly influence loan prediction.

**Scaling:** StandardScaler was used to normalize the data, ensuring models performed optimally.

### Modeling and Evaluation
**Models Used:**

- Logistic Regression
- Support Vector Classifier (SVC)
SVC outperformed Logistic Regression in accuracy and other metrics.
**Evaluation Metrics:**

Accuracy Score

Precision

Recall

F1 Score

Classification Report
### Results
Best Model: Support Vector Classifier

Performance: For class 0

- Precision: 88%
- Recall: 95%
- F1 Score: 91%

For class 1
- Precision: 94%
- Recall: 86%
- F1 Score: 90%

Overall Accuracy: 91%


### How to Use

Clone the repository:

git clone https://github.com/Techkene/Loan_prediction_status.git

cd loan_prediction_status

Install dependencies:

- pip install Pandas
- pip install NumPy
- pip install sklearn
- pip install Matplotlib 
- pip install Seaborn 

### Author
email: <keneanoliefo24@gmail.com>

username: `Techkene`

The results and metrics will be displayed after running the model.

### Conclusion

This project demonstrates a machine-learning approach to predicting loan status using a credit risk dataset. By employing robust feature selection and advanced modeling techniques, the final model achieved significant performance improvements.