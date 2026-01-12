This project develops a machine learning model to automate the loan eligibility process. By analyzing applicant profiles, the model predicts whether a loan will be approved based on factors such as credit history, income, education, and more.

# Loan Approval Prediction using Random Forest

## Project Overview

The goal of this project is to build a classification model that helps financial institutions streamline the loan approval process. The model uses a **Random Forest Classifier** to predict the `Loan_Status` (Approved or Denied) for applicants based on historical data.

## Key Features

* **Data Cleaning:** Handled missing values by removing null entries to ensure data integrity.
* **Feature Engineering:** * Converted categorical variables (Gender, Married, Education, etc.) into numerical values using manual mapping.
* Standardized the `Dependents` column (e.g., transforming "3+" into numerical format).


* **Predictive Modeling:** Implemented a **Random Forest Classifier** with a optimized `max_depth` to prevent overfitting.
* **Performance:** Achieved an accuracy score of **~78.5%** on the test dataset.

## Dataset Description

The dataset includes 614 applicant records with the following attributes:

* **Demographics:** Gender, Marital Status, Dependents, Education.
* **Financials:** Applicant Income, Co-applicant Income, Loan Amount, Loan Term.
* **Credit History:** A critical factor indicating past credit reliability.
* **Property Area:** Rural, Semi-urban, or Urban.

## Technologies Used

* **Language:** Python
* **Libraries:**
* `Pandas` & `NumPy` for data manipulation.
* `Scikit-Learn` for model training and evaluation.
* `Seaborn` for data visualization.



## How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/loan-approval-prediction.git

```


2. **Install dependencies:**
```bash
pip install pandas numpy scikit-learn seaborn

```


3. **Run the Notebook:** Open `loan_approval.ipynb` in Jupyter Lab or Notebook and execute the cells.

## Results

The model was evaluated using a **70/30 train-test split**. The Random Forest model provided a robust baseline with an accuracy of **78.47%**, identifying **Credit History** as a significant predictor for loan eligibility.

---
