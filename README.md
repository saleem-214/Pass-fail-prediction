# Student Performance Prediction - Logistic Regression

## 🎯 Objective
The goal of this project is to build a simple machine learning model using logistic regression to predict whether a student will **pass** or **fail** based on:
- Hours Studied
- Attendance Percentage

---

## 🛠 Code Overview
- **Dataset:** Created manually within the code using pandas DataFrame. Columns:
  - `Hours_Studied`
  - `Attendance`
  - `Pass_Fail` (1 = Pass, 0 = Fail)

- **Model:** Logistic Regression (from scikit-learn)
- **Steps:**
  1. Import necessary libraries (`pandas`, `matplotlib`, `sklearn`)
  2. Create and explore dataset
  3. Visualize data distribution using a scatter plot
  4. Split data into training and testing sets (80% / 20%)
  5. Train logistic regression model
  6. Evaluate using accuracy, confusion matrix, and classification report
  7. Accept user input for new data and predict pass/fail

---

## ⚙️ How It Works
- The model is trained to find the relationship between study hours + attendance and whether a student passes or fails.
- After training, it can predict pass/fail for new values entered by the user.
- Example:  
  If a user inputs `3` hours studied and `70`% attendance, the model will predict if that student is likely to pass.

---

## 📊 Result
The model achieved an accuracy of **(fill in after running your notebook)** on the test data.  
It outputs:
- **Pass** (if predicted class is 1)
- **Fail** (if predicted class is 0)

---

## 🚀 How to Run
1. Open the notebook (`student_performance_prediction.ipynb`) in Google Colab or Jupyter Notebook.
2. Run all cells in sequence.
3. Enter values when prompted for hours studied and attendance to get a prediction.


