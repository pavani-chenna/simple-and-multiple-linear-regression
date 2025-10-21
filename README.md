# 📊 Linear Regression on Student Scores & Petrol Consumption

This project demonstrates both *Simple Linear Regression* and *Multiple Linear Regression* using Python and scikit-learn. It includes a full ML pipeline: data cleaning, visualization, model training, evaluation, feature selection, and regularization.

---

## 📁 Datasets Used

1. student_scores.csv - Relationship between hours studied and student scores.
2. petrol_consumption.csv - Factors influencing petrol consumption across states.

---

## 🛠 Workflow Overview

### 🔹 1. Data Preprocessing
- Handled missing values and duplicates
- Outlier detection using IQR method
- Clipping outliers for better model stability

### 🔹 2. Exploratory Data Analysis (EDA)
- Correlation analysis
- Visual validation of linearity
- Feature-wise plotting for insights

### 🔹 3. Model Building

#### 🧮 Simple Linear Regression (Student Data)
- Linear regression to predict student scores based on study hours
- Achieved strong R² score, suggesting a high correlation

#### 🧮 Multiple Linear Regression (Petrol Data)
- Features used: Petrol_tax, Average_income, Population_Driver_licence(%)
- Feature scaling using StandardScaler
- Built baseline linear regression model

### 🔹 4. Model Evaluation
- R² Score
- Comparison of predicted vs actual values

### 🔹 5. Feature Selection
- Recursive Feature Elimination (RFE)
- Sequential Feature Selector (SFS)

### 🔹 6. Regularization
- Ridge Regression with cross-validation
- Tested multiple alpha values to avoid overfitting

---

## 📈 Results Summary

| Model                  | Dataset              | R² Score |
|-----------------------|----------------------|----------|
| Simple Linear Regression | Student Scores       | High     |
| Multiple Linear Regression | Petrol Consumption | Moderate |
| Ridge Regression (best alpha) | Petrol Data | Improved |

---

## 🧰 Libraries Used

- pandas, numpy
- matplotlib
- scikit-learn

---

## 🔍 Future Scope

- Add Lasso & ElasticNet
- Use polynomial regression where linearity fails
- Deploy models with a UI (Streamlit or Flask)

---

## 👨‍💻 Author

Pavani Chenna

LinkedIn: [(www.linkedin.com/in/pavani-chenna)]
