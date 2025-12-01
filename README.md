# IND2627 - Introduction to Statistical Learning

This repository contains homework assignments, exercises, and activities for the course **IND2627 - Introduction to Statistical Learning**. The content covers various machine learning and statistical analysis topics, implemented in Python using Jupyter Notebooks.

## 📚 Repository Content

### Homework Assignments

#### **Homework 1 - Multiple Linear Regression**
- **Exercise 1**: Exploratory data analysis and multiple linear regression
- **Exercise 2**: Model validation and residual analysis
- **Exercise 3**: Prediction and model evaluation
- **Datasets**: `Default.csv`, `Insurance.csv`

#### **Homework 2 - Regularization Methods and Variable Selection**
- **Exercise 1**: Best Subset Selection, Forward and Backward Stepwise Selection (Dataset: Hitters)
- **Exercise 2**: Ridge and LASSO Regression (Dataset: Hitters)
- **Exercise 3**: Principal Component Analysis (PCA) and Principal Component Regression (PCR) (Dataset: Boston Housing)
- **Topics**: L1/L2 Regularization, feature selection, dimensionality reduction

#### **Homework 3 - Non-Linear Models**
- **Exercise 1**: Polynomial Regression and Regression Splines (Dataset: Wage)
- **Exercise 2**: Smoothing Splines and Local Regression
- **Exercise 3**: Generalized Additive Models (GAMs)
- **Dataset**: `Wage.csv`

#### **Homework 4 - Support Vector Machines**
- **Main Notebook**: `Homework_4.ipynb`
- **Content**:
  - Maximal Margin Classifier
  - Support Vector Classifier
  - Kernels (Linear, Polynomial, RBF)
  - Practical application in binary classification
- **Dataset**: `Heart.csv` (Heart Disease dataset)

### Extra Activities

#### **Lecture 10 - Support Vector Machines**
- **Notebook**: `SVM_exercise.ipynb`
- **Dataset**: `Heart.csv`
- Additional exercises on theoretical and practical SVM concepts

## 🛠️ Technologies and Libraries

The project uses the following Python libraries:

### Data Analysis and Manipulation
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical operations and linear algebra

### Machine Learning and Statistical Modeling
- `scikit-learn` - Machine learning algorithms and preprocessing
- `statsmodels` - Statistical models and tests
- `patsy` - R-style statistical formulas

### Visualization
- `matplotlib` - Basic visualizations
- `seaborn` - Advanced statistical visualizations

### Notebooks
- `jupyter` - Interactive development environment
- `ipython` - Enhanced interactive shell

## 📋 Requirements

### Option 1: Using pip (requirements.txt)
```bash
pip install -r requirements.txt
```

### Option 2: Using Conda (environment.yml)
```bash
conda env create -f environment.yml
conda activate ind2627-stats
```

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/santiago-v-2013/IND2627_Intro_Stat.git
cd IND2627_Intro_Stat/Subject
```

2. Install dependencies (see Requirements section)

3. Start Jupyter Notebook:
```bash
jupyter notebook
```

4. Navigate to the desired folder and open the corresponding notebook

## 📂 Directory Structure

```
Subject/
├── README.md
├── LICENSE
├── requirements.txt
├── environment.yml
├── homework_1/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   ├── exercise_3.ipynb
│   └── datasets/
│       ├── Default.csv
│       └── Insurance.csv
├── homework_2/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   └── exercise_3.ipynb
├── homework_3/
│   ├── exercise_1.ipynb
│   ├── exercise_2.ipynb
│   ├── exercise_3.ipynb
│   └── datasets/
│       └── Wage.csv
├── homework_4/
│   ├── Homework_4.ipynb
│   └── datasets/
│       └── Heart.csv
└── Extra_Activities/
    └── Lecture_10/
        ├── SVM_exercise.ipynb
        └── datasets/
            └── Heart.csv
```

## 📖 Topics Covered

1. **Linear Regression** - Simple and multiple linear models
2. **Regularization** - Ridge, LASSO, Elastic Net
3. **Variable Selection** - Best Subset, Forward/Backward Selection
4. **Dimensionality Reduction** - PCA, PCR
5. **Non-Linear Models** - Polynomials, Splines, GAMs
6. **Support Vector Machines** - Classification with different kernels
7. **Model Validation** - Cross-validation, Test/Train split
8. **Model Evaluation** - MSE, RMSE, R², AIC, BIC, ROC-AUC

## 📝 Important Notes

- Some datasets are loaded from external sources when not available locally
- The Boston Housing dataset is used with caution due to ethical considerations mentioned in the notebooks
- All notebooks include detailed documentation and step-by-step explanations

## 👤 Author

Santiago V.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
