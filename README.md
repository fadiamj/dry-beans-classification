# Dry Bean Classification Using Machine Learning

A university machine learning project focused on **multiclass classification of seven dry bean varieties** using four supervised learning algorithms: K-Nearest Neighbors, Decision Tree, Random Forest, and Artificial Neural Network.

The project explores data preprocessing, model training, hyperparameter tuning, and performance evaluation to compare how different machine learning approaches classify dry beans.

## Project Overview

Accurately identifying dry bean varieties can support automation and quality control in agricultural and food production processes. This project investigates how machine learning can distinguish between seven bean varieties based on their measured characteristics.

Using the Dry Bean Dataset, we developed and evaluated four classification models and compared their performance using the **Macro-Averaged F1 Score**, which gives equal importance to each class.

## Dataset

The dataset contains:

- **13,611 samples**
- **16 input features**
- **7 target classes**, representing different dry bean varieties

The features describe physical characteristics of dry beans and are used to predict their variety.

## Machine Learning Models

Four supervised learning algorithms were implemented and compared:

| Model | Description |
|---|---|
| K-Nearest Neighbors (KNN) | Classifies a sample based on the labels of its nearest neighbors. |
| Decision Tree | Uses a series of decision rules to classify samples. |
| Random Forest | Combines multiple decision trees to improve predictive performance and generalization. |
| Artificial Neural Network (ANN) | Learns complex patterns in the data through interconnected computational layers. |

## Data Preprocessing and Methodology

The project report describes the following preprocessing and modeling steps:

- **Data cleaning:** Removing duplicate records.
- **Feature scaling:** Standardizing feature values where appropriate for the selected algorithms.
- **Class imbalance handling:** Applying class weights to help account for differences in class frequencies.
- **Dimensionality reduction:** Exploring Principal Component Analysis (PCA) to reduce feature dimensionality.
- **Hyperparameter tuning:** Adjusting model parameters to improve validation performance.
- **Model evaluation:** Comparing performance on validation and test sets.

The experimental design described in the report uses a stratified 70% training, 15% validation, and 15% test split.

## Results

The following Macro F1 scores were reported in the university project report.

| Model | Test Macro F1 Score |
|---|---:|
| K-Nearest Neighbors (KNN) | 0.944 |
| Random Forest | 0.942 |
| Artificial Neural Network (ANN) | 0.940 |
| Decision Tree | 0.917 |

KNN achieved the highest reported test Macro F1 score of **0.944**, followed closely by Random Forest and the Artificial Neural Network.

The results indicate that all four models achieved promising classification performance, with some differences in their ability to generalize to unseen data.

*Note: These results are transcribed from the project report and have not been independently reproduced.*

## Evaluation Metrics and Visualizations

The project report describes the use of:

- Macro-Averaged F1 Score for comparing model performance.
- Confusion matrices for examining classification errors.
- Training and validation loss and accuracy plots for monitoring ANN learning.
- A decision tree visualization for examining the model's decision rules.
- Performance comparisons across the four classification algorithms.

## Repository Contents

| File | Description |
|---|---|
| `dry-beans-classification.ipynb` | Jupyter Notebook containing the project's analysis and machine learning implementation. |
| `project-report.pdf` | University project report documenting the methodology, experiments, and findings. |

## Getting Started

### Prerequisites

- Python 3
- Jupyter Notebook or JupyterLab
- The Python libraries required by the notebook, such as pandas, NumPy, Matplotlib, Seaborn, and scikit-learn, where used.

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone https://github.com/fadiamj/dry-beans-classification.git
   ```

2. Navigate to the project directory:

   ```bash
   cd dry-beans-classification
   ```

3. Install the required libraries based on the notebook's imports.

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `dry-beans-classification.ipynb` and run the notebook cells in order.

## Project Documentation

For a detailed explanation of the problem, experimental design, model configurations, and findings, see the university project report:

**[Read the Project Report](project-report.pdf)**

## Key Takeaways

This project provided practical experience with:

- Preparing data for machine learning.
- Building and comparing multiple classification models.
- Tuning model hyperparameters.
- Evaluating multiclass classification performance.
- Interpreting model results using metrics and visualizations.

The project demonstrates the application of supervised machine learning techniques to a real-world-style classification problem and highlights the trade-offs between predictive performance and model interpretability.

---

**Project Type:** University Machine Learning Project  
**Domain:** Machine Learning · Supervised Learning · Multiclass Classification  
**Tools:** Python · Jupyter Notebook · scikit-learn
