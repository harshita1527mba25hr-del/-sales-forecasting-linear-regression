Sales Forecasting using Linear Regression
##  Project Overview
This project demonstrates a simple implementation of **Sales Forecasting** using **Linear Regression** in Python. The model predicts future sales based on historical daily sales data.

The project is part of **Week 2 Lab 13–14** and focuses on understanding basic machine learning workflow including:
- Data preparation
- Model training
- Prediction
- Data visualization

---

## Objectives
- Understand how Linear Regression works
- Convert date-based data into numerical format
- Train a machine learning model using Scikit-learn
- Predict future values
- Visualize results using graphs

---

##  Dataset Description
The dataset is manually created and contains:
- **Date**: Daily records from Jan 1 to Jan 10, 2024
- **Sales**: Sales values for each day

---

##  Steps Performed

### 1. Data Creation
- Created a dataset using Python dictionary
- Converted it into a Pandas DataFrame

### 2. Data Preprocessing
- Converted date column to datetime format
- Created a new feature: **day_number** (numerical representation of days)

### 3. Model Training
- Used **Linear Regression** from Scikit-learn
- Trained the model using:
  - Input (X): Day Number
  - Output (y): Sales

### 4. Prediction
- Predicted sales for **Day 11**

### 5. Visualization
- Plotted:
  - Actual data points (scatter plot)
  - Regression line (predicted trend)

---

##  Output
- Predicted Sales for Day 11: **~446.67**
- Graph showing sales trend and regression line

---

##  Tools & Technologies Used
- **Python**
- **Google Colab** (for development and execution)
- **Pandas** (data handling)
- **Matplotlib** (data visualization)
- **Scikit-learn** (machine learning model)

---

##  Visualization
The project includes a graph that shows:
- Actual sales data points
- Linear regression prediction line

---

##  How to Run the Project

1. Open Google Colab or any Python environment
2. Copy and paste the code
3. Run all cells
4. View prediction output and graph

---

##  Learning Outcomes
- Gained understanding of regression models
- Learned basic feature engineering
- Understood how predictions are made
- Visualized data trends effectively

---

##  Future Improvements
- Use larger and real-world datasets
- Apply advanced models (Polynomial Regression, Time Series)
- Add accuracy evaluation metrics
- Deploy as a web application

---

##  Author
**Harshita**
