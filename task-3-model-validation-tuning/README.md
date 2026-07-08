# Task 3: Model Validation and Hyperparameter Tuning

## 📌 Objective

The objective of this task is to improve the performance of a Machine Learning model by applying Model Validation and Hyperparameter Tuning techniques on the California Housing Dataset. Multiple regression models are evaluated using Cross Validation, and the best model is selected through GridSearchCV.

---

## 📂 Dataset

- **Dataset:** California Housing Dataset (housing.csv)
- **Target Variable:** median_house_value

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📋 Workflow

### 1. Import Libraries
Imported all required Machine Learning and Data Analysis libraries.

### 2. Load Dataset
Loaded the California Housing Dataset into a Pandas DataFrame.

### 3. Dataset Exploration
- Displayed dataset information
- Checked dataset dimensions
- Generated descriptive statistics

### 4. Data Cleaning
- Checked missing values
- Filled missing values in **total_bedrooms**
- Converted categorical variables using One-Hot Encoding

### 5. Data Visualization
Created:
- House Price Distribution Histogram
- Correlation Heatmap

### 6. Feature Selection
Separated independent variables (X) and target variable (y).

### 7. Train-Test Split
Split the dataset into training and testing sets using an 80:20 ratio.

### 8. Feature Scaling
Applied StandardScaler to normalize feature values.

### 9. Model Validation
Performed Cross Validation on:
- Linear Regression
- Ridge Regression
- Decision Tree Regressor

### 10. Hyperparameter Tuning
Applied GridSearchCV to optimize Ridge Regression hyperparameters.

### 11. Model Evaluation
Evaluated the best model using:
- RMSE (Root Mean Squared Error)
- R² Score

### 12. Visualization
Generated an Actual vs Predicted House Prices scatter plot.

---

## 📊 Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Decision Tree Regressor

---

## 📈 Evaluation Metrics

- Root Mean Squared Error (RMSE)
- R² Score
- Cross Validation Score

---

## 🏆 Best Model

**Ridge Regression**

Reason:
- Highest Cross Validation Score
- Better Generalization
- Lower RMSE
- Higher R² Score

---

## 📁 Project Structure

summerix-global-ai-ml-internship-yash-kunjir

├── task-1-house-price-predictor

├── task-2-model-comparison

└── task-3-model-validation-tuning
    ├── housing.csv
    ├── task3_model_validation_tuning.ipynb
    └── README.md

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/yashkunjir2006-commits/summerix-global-ai-ml-internship-yash-kunjir.git
```

2. Navigate to Task 3.

```bash
cd task-3-model-validation-tuning
```

3. Install required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open:

```
task3_model_validation_tuning.ipynb
```

6. Run all notebook cells.

---

## 📌 Learning Outcomes

- Data Cleaning
- Feature Engineering
- Feature Scaling
- Cross Validation
- Hyperparameter Tuning
- GridSearchCV
- Model Evaluation
- Performance Comparison
- Regression Analysis

---

## 👨‍💻 Author

**Yash Kunjir**

AI & ML Virtual Internship

Summerix Global

GitHub:
https://github.com/yashkunjir2006-commits/summerix-global-ai-ml-internship-yash-kunjir