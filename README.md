# 🎓 Student Performance Prediction

This project predicts whether a student will **Pass** or **Fail** based on their study habits, attendance, parental support, and other features using a machine learning model.

---

## 📌 Problem Statement

> **Predict if a student will pass or fail based on attendance, previous scores, and study habits.**

---

## 🧠 Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn (ML)
- Seaborn, Matplotlib (Visualization)

---

## 📂 Dataset Information

- **Source**: Uploaded via Google Drive  
- **Size**: ~2300 students  
- **Features**:
  - `StudentID`
  - `Age`
  - `Gender`
  - `Ethnicity`
  - `ParentalEducation`
  - `StudyTimeWeekly`
  - `Absences`
  - `Tutoring`
  - `ParentalSupport`
  - `Extracurricular`
  - `Sports`
  - `Music`
  - `Volunteering`
  - `GPA`
  - `GradeClass` → Transformed to `Pass/Fail`

---

## ⚙️ Methodology

1. **Load** and explore dataset.
2. **Create target** variable (`Pass/Fail`) from `GradeClass`.
3. **Select features** (study habits, absences, etc.).
4. **Preprocess**: Encoding, Scaling.
5. **Split** data into training and testing sets.
6. **Train** a Random Forest Classifier.
7. **Evaluate** model with accuracy score, confusion matrix, classification report.
8. **Visualize** feature importance, confusion matrix, accuracy.
9. **Predict and display** results of first 20 students.

---

## 🎯 Algorithm Used

> **Random Forest Classifier**

- Ensemble model of decision trees.
- Avoids overfitting.
- Provides feature importance.
- Great for classification problems.

---

## 📈 Evaluation Metrics

- **Accuracy**
- **Precision / Recall / F1-score**
- **Confusion Matrix**

---

## 📊 First 20 Students - Predicted Results

| Student ID | Predicted Label |
|------------|------------------|
| 1001       | Pass             |
| 1002       | Fail             |
| 1003       | Pass             |
| 1004       | Pass             |
| 1005       | Pass             |
| 1006       | Fail             |
| 1007       | Pass             |
| 1008       | Pass             |
| 1009       | Pass             |
| 1010       | Pass             |
| 1011       | Pass             |
| 1012       | Fail             |
| 1013       | Pass             |
| 1014       | Pass             |
| 1015       | Fail             |
| 1016       | Fail             |
| 1017       | Pass             |
| 1018       | Pass             |
| 1019       | Pass             |
| 1020       | Fail             |

> 📎 *These predictions were made using a trained Random Forest model. "Pass" means the student was predicted to pass based on their features.*

---

## 📊 Visualization Samples

- **Confusion Matrix**
- **Model Accuracy**
- **Feature Importance**

---

## 📥 Output File

- `student_predictions.csv` → Contains predictions for all students.

---

## ✅ Conclusion

This project successfully demonstrates how machine learning can predict student outcomes based on behavioral and academic data. It can help educational institutions identify students who might need support early on.

---

## 🙋‍♂️ Author

Made by a B.Tech first-year student as part of an academic project.

