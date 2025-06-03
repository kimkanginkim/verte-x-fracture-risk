# VERTE-X Hip Fracture Risk Prediction
This project aims to predict the 10-year risk of major osteoporotic fractures (FRAX-MOF) using machine learning techniques.

## 🔍 Project Overview
As part of the "Statistical Machine Learning Theory" course at Ewha Womans University, this project focused on improving predictive performance based on real-world structured health data.

## 🛠 What I Did
- Performed **data preprocessing**:
  - Handled missing values
  - Encoded categorical features
  - Applied `StandardScaler` for feature scaling
  - Split data into training and test sets
- Computed **feature importance** using `RandomForestRegressor`
  - Selected top 10 most important features
- Trained and compared **three models**:
  - `GradientBoostingRegressor`
  - `RandomForestRegressor`
  - `MLPRegressor`
- Evaluated model performance based on **R² score**
- Applied the best-performing model to the test set and exported predictions

## 📊 Outcome
Improved model generalization and efficiency by selecting meaningful features and optimizing model performance.

## 💡 Tools Used
- Python (pandas, scikit-learn, matplotlib)
- Jupyter Notebook

---

Feel free to explore the code and reach out if you have any questions!
