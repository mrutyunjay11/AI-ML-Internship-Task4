# Logistic Regression - Breast Cancer Classification

This project demonstrates how to use Logistic Regression for binary classification on the Breast Cancer Wisconsin dataset. The workflow includes data preprocessing, model training, evaluation, and visualization of the sigmoid function and ROC-AUC curve.

## Author

Mrutyunjay Joshi

## Dataset

- [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Place `data.csv` in the project directory.

## Steps

1. **Import Libraries**  
   Uses `pandas`, `numpy`, `matplotlib`, and `scikit-learn`.

2. **Load and Preprocess Data**  
   - Loads `data.csv`.
   - Drops unnecessary columns (`id`, `Unnamed: 32`).
   - Encodes target variable: Malignant (`M`) as 1, Benign (`B`) as 0.

3. **Split Data**  
   - Separates features and target.
   - Splits into training and testing sets (80/20).

4. **Standardize Features**  
   - Scales features using `StandardScaler`.

5. **Train Model**  
   - Fits `LogisticRegression` on the training data.

6. **Make Predictions**  
   - Predicts labels and probabilities for the test set.

7. **Evaluate Model**  
   - Prints confusion matrix, classification report, and accuracy score.

8. **Plot ROC-AUC Curve**  
   - Visualizes the ROC curve and computes AUC.

9. **Visualize Sigmoid Function**  
   - Plots the sigmoid function used in logistic regression.

## Usage

Open `Task 4.ipynb` in VS Code or Jupyter Notebook and run each cell sequentially.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Output

- Model evaluation metrics (accuracy, confusion matrix, classification report)
- ROC-AUC curve plot
- Sigmoid function plot
