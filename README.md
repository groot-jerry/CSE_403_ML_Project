# Multivariable Linear Regression on Diabetes Dataset

##  Project Overview

This project demonstrates the implementation of **Multivariable Linear Regression** using the **Pima Indians Diabetes Dataset** in two different ways:

1. **Linear Regression from Scratch (Without Scikit-learn)**
2. **Linear Regression Using Scikit-learn**

The objective is to compare both approaches in terms of implementation complexity, performance, accuracy, and ease of use while gaining a deeper understanding of how linear regression works internally.

---

##  Objectives

* Understand the mathematical foundation of multivariable linear regression.
* Implement gradient descent manually without using machine learning libraries.
* Train and evaluate a linear regression model using Scikit-learn.
* Compare the performance of both implementations.
* Analyze the advantages and disadvantages of each approach.

---

##  Dataset

**Dataset:** Pima Indians Diabetes Dataset

The dataset originates from the **National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)**.

Its purpose is to predict whether a patient has diabetes based on several medical measurements.

### Dataset Features

| Feature                  | Description                       |
| ------------------------ | --------------------------------- |
| Pregnancies              | Number of pregnancies             |
| Glucose                  | Plasma glucose concentration      |
| BloodPressure            | Diastolic blood pressure (mm Hg)  |
| SkinThickness            | Triceps skin fold thickness (mm)  |
| Insulin                  | 2-Hour serum insulin              |
| BMI                      | Body Mass Index                   |
| DiabetesPedigreeFunction | Diabetes pedigree function        |
| Age                      | Age of the patient                |
| Outcome                  | Diabetes status (0 = No, 1 = Yes) |

> **Note:** Although this dataset is commonly used for **classification**, it is used here for educational purposes to demonstrate multivariable linear regression.

---

##  Technologies Used

* Python
* Google Colab / Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

##  Project Workflow

### 1. Data Loading

* Load the dataset using Pandas.
* Display the first few rows.
* Check for missing values.

### 2. Data Preprocessing

* Separate input features and target variable.
* Split the dataset into training and testing sets.

### 3. Linear Regression from Scratch

* Initialize model parameters.
* Implement Gradient Descent.
* Calculate predictions manually.
* Update weights iteratively.
* Evaluate model performance.

### 4. Linear Regression Using Scikit-learn

* Import `LinearRegression`.
* Train the model.
* Predict the target values.
* Evaluate the model.

### 5. Performance Comparison

Compare both implementations using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

---

##  Evaluation Metrics

The following metrics are used to evaluate model performance:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

##  Comparison

| Feature           | From Scratch            | Scikit-learn         |
| ----------------- | ----------------------- | -------------------- |
| Implementation    | Manual                  | Library-Based        |
| Complexity        | High                    | Low                  |
| Training Speed    | Slower                  | Faster               |
| Optimization      | Manual Gradient Descent | Optimized Algorithms |
| Ease of Use       | Moderate                | Very Easy            |
| Educational Value | Excellent               | Good                 |
| Code Length       | Longer                  | Shorter              |

---

##  How to Run

### Clone the Repository

bash
git clone https:/github.com/groot-jerry/CSE_403_ML_Project.git


### Navigate to the Project

```bash
cd CSE_403_ML_Project
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib scikit-learn
```

### Open the Notebook

Run the notebooks using:

* Google Colab
* Jupyter Notebook
* VS Code

Execute all cells sequentially.

---

##  Learning Outcomes

After completing this project, you will understand:

* How multivariable linear regression works internally.
* The mathematics behind Gradient Descent.
* How Scikit-learn simplifies machine learning implementation.
* The differences between manual implementation and machine learning libraries.
* Model evaluation using common regression metrics.

---

##  Future Improvements

* Implement Logistic Regression for the diabetes prediction task.
* Add feature scaling and normalization.
* Compare additional machine learning algorithms.
* Perform hyperparameter tuning.
* Visualize regression performance and residual errors.

---

##  Author

**Junaed Hossain Jibon**

Department of Computer Science and Engineering (CSE)

University of Asia Pacific

---

## 📄 License

This project was developed for educational and academic purposes.
