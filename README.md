#  Diabetes Prediction using Linear Regression

Hey there! 
This is a small machine learning project I worked on as part of my learning journey in ML. I used the **Diabetes dataset** from scikit-learn to predict how the disease might progress in a patient based on some health-related features.

---

##  What I Did

- Used **Linear Regression** to predict the target (disease progression score)
- Evaluated the model using common regression metrics like **R², MAE, MSE, and RMSE**
- Tried something different — converted the regression output into a **binary classification** problem using the **median value** as a threshold
- Evaluated classification performance using **accuracy**, **confusion matrix**, and **classification report**
- Visualized the results with **matplotlib**

---

##  Dataset Info

- Comes from: `sklearn.datasets.load_diabetes()`
- It includes 10 medical features like:
  - Age
  - Sex
  - BMI
  - Blood Pressure
  - and 6 other basic lab measurements
- Target: A number representing the progression of diabetes after 1 year

---

## ML Concepts Used

- **Linear Regression** (from `sklearn.linear_model`)
- Train-test split
- Regression Metrics:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- Basic **binary classification** using threshold
- **Confusion Matrix** & **Classification Report**

---

##  Visualizations

- **Confusion Matrix** (to see how well the model performs after converting to classification)
- **Actual vs Predicted** scatter plot (to visualize regression performance)

You can see the plots by running the code or checking the images in the repo.

---

##  Libraries Used

- Python 
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## ▶️ How to Run

```bash
pip install numpy pandas matplotlib scikit-learn
python diabetes_regression.py
