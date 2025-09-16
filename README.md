# skillcraft-tech_DS_task3
Bank Marketing Decision Tree Classifier Predict whether a customer will subscribe to a term deposit using the Bank Marketing dataset. This project uses a Decision Tree classifier on demographic and behavioral features, including age, job, balance, and campaign interactions, with model evaluation via accuracy and classification metrics.

# Bank Marketing Decision Tree Classifier

## Project Overview
This project builds a **Decision Tree Classifier** to predict whether a bank customer will subscribe to a term deposit based on demographic and behavioral data. Using the **Bank Marketing dataset** from the UCI Machine Learning Repository, the model considers features like age, job, marital status, education, account balance, housing and personal loans, contact information, and campaign details.

## Dataset
- **Source:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Number of Instances:** 45,211
- **Features:** age, job, marital, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome
- **Target Variable:** `y` (whether the client subscribed to a term deposit: yes/no)

## Key Steps
1. Load the CSV dataset using `pandas`.
2. Explore and preprocess data, including handling categorical features with `LabelEncoder`.
3. Split the dataset into training and testing sets.
4. Train a **Decision Tree Classifier** using `scikit-learn`.
5. Evaluate model performance with **accuracy**, **confusion matrix**, and **classification report**.

## Installation
Ensure Python is installed. Then, install the required libraries:

```bash
pip install pandas scikit-learn
````

## Usage

1. Download the dataset `bank.csv` from the UCI repository.
2. Place the CSV in your project directory.
3. Run the Python script:

```bash
python decision_tree_bank.py
```

4. The console will display:

   * Model accuracy
   * Classification report
   * Confusion matrix

## Visuals
##
![image alt](https://github.com/Srinidhi1009/skillcraft-tech_DS_task3/blob/6d20ccd226af048fcc672c185f779819db08ab67/Screenshot%202025-09-16%20123358.png)

##
![image alt]()

## Results

The Decision Tree provides a baseline for predicting customer subscription behavior. Further improvements can include:

* Hyperparameter tuning
* Using ensemble methods like Random Forest or Gradient Boosting
* Feature engineering to improve predictive power


