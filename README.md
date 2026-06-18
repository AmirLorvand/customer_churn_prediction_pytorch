# Customer Churn Prediction with PyTorch

This project is a machine learning and deep learning coursework project focused on **customer churn prediction**. It was developed for the **Bachelor’s Advanced Topics in AI and Data Science** module.

The project uses customer data to predict whether a customer is likely to churn. The notebook includes data exploration, preprocessing, feature engineering, model training, hyperparameter testing, and evaluation using a PyTorch neural network.

---

## Project Timeline

* **Originally completed:** 2024
* **Refactored and published on GitHub:** 2026
* **Context:** Bachelor’s Advanced Topics in AI and Data Science coursework project

This repository has been cleaned and documented for portfolio purposes.

---

## Dataset

The dataset used in this project is the **Customer Churn Dataset** from Kaggle by Muhammad Shahid Azeem.

The dataset is **not included** in this repository.
Please download it from Kaggle using the dataset link provided inside the notebook.

After downloading, place the CSV files in a local `data/` folder using this structure:

```text
data/
├── customer_churn_dataset-training-master.csv
└── customer_churn_dataset-testing-master.csv
```

The `data/` folder is intentionally ignored by Git to avoid uploading external dataset files.

---

## Project Features

* Customer churn prediction
* Exploratory Data Analysis
* Missing value handling
* Feature engineering
* Categorical encoding
* Feature scaling and normalisation
* Train/test preparation
* PyTorch MLP neural network
* Hyperparameter testing
* Model evaluation using classification metrics
* Confusion matrix visualisation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
* PyTorch
* Jupyter Notebook

---

## Project Structure

```text
.
├── customer_churn_prediction_pytorch.ipynb
├── README.md
├── requirements.txt
└── .gitignore
---

## How to Run

1. Clone the repository.

2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle using the link provided in the notebook.

4. Create a `data/` folder in the project root.

5. Place the training and testing CSV files inside the `data/` folder.

6. Open the notebook:

customer_churn_prediction_pytorch.ipynb

7. Run the notebook cells from top to bottom.

---

## Model Summary

The project uses a PyTorch-based Multi-Layer Perceptron for binary classification. The model is trained to predict whether a customer is likely to churn based on available customer features.

The notebook includes preprocessing steps, model training, and evaluation using metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion matrix

---

## What I Learned

Through this coursework project, I practised:

* Building a complete machine learning workflow
* Performing exploratory data analysis
* Cleaning and preprocessing tabular data
* Encoding categorical variables
* Normalising numerical features
* Building a neural network using PyTorch
* Training and evaluating a classification model
* Testing different hyperparameters
* Interpreting classification metrics
* Preparing a data science notebook for GitHub presentation

---

## Future Improvements

Possible improvements include:

* Adding comparison with classical machine learning models such as Logistic Regression, Random Forest, and XGBoost
* Improving feature selection
* Adding cross-validation
* Adding ROC-AUC analysis
* Improving class imbalance handling
* Saving the trained model
* Refactoring notebook code into Python scripts
* Adding a clearer experiment results table

---

## Author

**Amir Lorvand**

