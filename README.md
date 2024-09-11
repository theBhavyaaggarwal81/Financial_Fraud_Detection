# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using various machine learning models. The dataset used for this project contains transactions labeled as fraudulent or non-fraudulent. The models developed include:

- XGBoost
- Logistic Regression
- Random Forest
- Naive Bayes
- Decision Tree


Dataset link : https://docs.google.com/spreadsheets/d/1165BBQHrrpXJaUnzCeUj0Jx2W6JkAfHV/edit?usp=sharing&ouid=114468191924083002314&rtpof=true&sd=true

The performance of these models is compared based on their **F1 Score**, which balances precision and recall.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Developed](#models-developed)
- [Model Comparison](#model-comparison)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Introduction

Credit card fraud is a significant issue in the financial industry. This project aims to develop and compare different machine learning models to effectively identify fraudulent transactions. The main objective is to find the most reliable model that balances **accuracy** and **efficiency**.

## Dataset

The dataset used in this project is highly imbalanced, with a very low percentage of fraudulent transactions. It has been pre-processed and is included in the repository.

- **File**: `processed_dataset.csv`

## Models Developed

The following machine learning models were developed to detect credit card fraud:

1. **XGBoost**: A scalable and accurate implementation of gradient boosting.
2. **Logistic Regression**: A statistical model that uses a logistic function to model a binary dependent variable.
3. **Random Forest**: An ensemble learning method that operates by constructing multiple decision trees.
4. **Naive Bayes**: A simple probabilistic classifier based on applying Bayes' theorem.
5. **Decision Tree**: A model that uses a tree-like graph of decisions.

## Model Comparison

The models were compared based on their **F1 Scores**, a metric that balances precision and recall, making it suitable for datasets with imbalanced classes like this one. The F1 Score is the harmonic mean of precision and recall.

## Conclusion

This project demonstrates the effectiveness of different machine learning models in detecting fraudulent transactions. Based on the model comparison, **[Model Name]** stood out as the best performer.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/credit-card-fraud-detection.git
    ```

2. Navigate to the project directory:
    ```bash
    cd credit-card-fraud-detection
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. Open and run `data.ipynb` to load and process the dataset.

6. Open and run `Visualization.ipynb` to visualize the results.

## Dependencies

This project requires the following Python packages:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

Install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

##Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to submit a Pull Request.


