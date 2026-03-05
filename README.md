# Tips Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## Project Description

This project demonstrates the implementation of a **Linear Regression model** to predict restaurant tips based on several features from the **Tips dataset**. The goal is to analyze how factors such as total bill amount, number of people, and categorical attributes influence tipping behavior.

The notebook walks through the complete machine learning workflow including **data preprocessing, feature encoding, model training, and performance evaluation**.

This project was created as part of learning the fundamentals of **Machine Learning using Python and Scikit-learn**.

---

## Dataset Information

The project uses the **Tips dataset**, a commonly used dataset in data analysis and machine learning tutorials.

### Dataset Features

| Feature    | Description                      |
| ---------- | -------------------------------- |
| total_bill | Total bill amount                |
| sex        | Gender of the customer           |
| smoker     | Whether the customer is a smoker |
| day        | Day of the week                  |
| time       | Lunch or dinner                  |
| size       | Number of people at the table    |
| tip        | Tip amount (Target Variable)     |

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Machine Learning Workflow

### 1. Data Exploration

* Inspect dataset structure
* Understand variable relationships
* Identify categorical and numerical features

### 2. Data Preprocessing

* Handling categorical variables using **One-Hot Encoding**
* Splitting data into **training and testing sets**

### 3. Model Training

A **Linear Regression model** from Scikit-learn is trained on the processed dataset.

### 4. Model Evaluation

The model performance is evaluated using:

* R² Score
* Prediction comparison
* Model accuracy interpretation

---

## Results

The trained model successfully learns patterns between customer bill characteristics and the tip amount. Evaluation metrics indicate the model can explain a portion of the variance in tipping behavior.

Example evaluation metric:

R² Score ≈ **0.82**

---

## Project Structure

```
Tips-Linear-Regression
│
├── Tips-Linear_Regression.ipynb   # Main machine learning notebook
├── README.md                      # Project documentation
```

---

## How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/sarthakchauhan255-hub/tips-prediction-linear-regression.git
```

### 2. Navigate to the Project Folder

```
cd tips-prediction-linear-regression
```

### 3. Install Required Libraries

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 4. Start Jupyter Notebook

```
jupyter notebook
```

Open the notebook and run the cells sequentially.

---

## Learning Outcomes

Through this project the following machine learning concepts were practiced:

* Linear Regression
* Feature Encoding
* Data Preprocessing
* Model Evaluation
* Basic Machine Learning Pipeline

---

## Future Improvements

Possible extensions to this project include:

* Implement **Polynomial Regression**
* Compare performance with **Random Forest Regression**
* Perform advanced **feature engineering**
* Add **visualization dashboards**

---

## Author

Sarthak Chauhan
B.Tech Computer Science Student
