# 🎓 Student Performance Prediction

This project aims to predict whether a student will **pass or fail** based on key factors such as attendance, previous scores, and study habits using **machine learning** techniques.

---

## 📌 Problem Statement

> **Objective:** Build a classification model to determine if a student will pass or fail using input features like:
- Attendance
- Study Time per Week
- Number of Absences
- Tutoring
- Parental Support
- Extracurricular Activities
- Sports, Music, and Volunteering Participation

---

## 🧠 Methodology

### 1. **Data Collection**
- Dataset containing ~2300 students loaded from a CSV file.
- Each row represents a student with their academic behavior and performance.

### 2. **Data Cleaning**
- Checked for null/missing values.
- Ensured column names are correct.
- Removed inconsistencies.

### 3. **Feature Engineering**
- Selected important features that impact academic results.
- Created a binary `Pass/Fail` label from the `GradeClass` column.

### 4. **Preprocessing**
- Encoded labels (`Pass` = 1, `Fail` = 0).
- Scaled features using `StandardScaler`.
- Split dataset into **80% training** and **20% testing** sets.

### 5. **Model Training**
- Used `Random Forest Classifier` for its robustness and accuracy.
- Trained on scaled data and evaluated using classification metrics.

### 6. **Evaluation Metrics**
- **Accuracy Score**
- **Classification Report** (Precision, Recall, F1-score)
- **Confusion Matrix**

### 7. **Visualization**
- Accuracy score bar chart.
- Confusion matrix heatmap.
- Feature importance bar chart.

### 8. **Result Presentation**
- Displayed prediction results for the **first 20 students**.
- Exported all predictions to a CSV file.

---

## 🗃 Dataset

**Filename:** `Student Performance Prediction.csv`

**Columns Used:**
- `StudyTimeWeekly`
- `Absences`
- `Tutoring`
- `ParentalSupport`
- `Extracurricular`
- `Sports`
- `Music`
- `Volunteering`
- `GradeClass` ➜ used to derive `Pass/Fail`

---

## 📈 Results

| Metric            | Value (Example) |
|-------------------|-----------------|
| Accuracy          | 0.89            |
| Precision (Pass)  | 0.91            |
| Recall (Pass)     | 0.94            |
| F1-score (Pass)   | 0.92            |

✅ Confusion Matrix and feature importance graphs included.

📄 CSV output generated: `student_predictions.csv`

---

## 📊 Sample Output (First 20 Students)

| Student_ID | Predicted | Predicted_Label |
|------------|-----------|-----------------|
| 101        | 1         | Pass            |
| 102        | 0         | Fail            |
| ...        | ...       | ...             |

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-performance-prediction.git
