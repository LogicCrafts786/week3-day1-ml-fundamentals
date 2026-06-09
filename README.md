
# week3-day1-ml-fundamentals
# 🎓 Week 3 Day 1 — Machine Learning Fundamentals Challenge

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.0+-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen.svg)

---

## 📌 Project Description

This project is part of the **AIML Internship Week 3 Day 1 Assignment**. It demonstrates core Machine Learning concepts using a student performance dataset. We build a **Linear Regression** model to predict a student's final score based on study hours, attendance, and previous academic performance.

The project is designed to be **beginner-friendly**, with detailed explanations, well-commented code, and rich visualizations using Plotly.

---

## 🎯 Objectives

- Understand the end-to-end Machine Learning workflow
- Load, explore, and visualize a real-world style dataset
- Build and train a Linear Regression model
- Evaluate model performance using MAE and R² Score
- Make predictions for new student data
- Create interactive visualizations using Plotly

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical operations |
| Scikit-learn | ML model, train-test split, evaluation |
| Plotly Express | Interactive data visualizations |
| Jupyter Notebook | Interactive development environment |

---

## 📁 Project Structure

```
week3-day1-ml-fundamentals/
│
├── student_performance.csv   # Dataset with 110 student records
├── assignment.ipynb          # Main Jupyter Notebook (all code + explanations)
├── ml_workflow.txt           # Written explanation of the ML workflow
├── answers.txt               # Answers to 15 conceptual ML questions
├── README.md                 # This file
└── screenshots/              # (Add after running the notebook)
    ├── 01_dataset_preview.png
    ├── 02_dataset_statistics.png
    ├── 03_train_test_split.png
    ├── 04_model_coefficients.png
    ├── 05_new_predictions.png
    ├── 06_actual_vs_predicted.png
    ├── 07_mae_r2_output.png
    ├── 08_scatter_hours_score.png
    ├── 09_scatter_attendance_score.png
    ├── 10_scatter_prevscore_score.png
    ├── 11_histogram_score.png
    └── 12_correlation_heatmap.png
```

---

## 🔄 Machine Learning Workflow

```
Data Collection
      ↓
Data Preparation & Cleaning
      ↓
Feature Selection
      ↓
Train-Test Split (80% / 20%)
      ↓
Model Training (Linear Regression)
      ↓
Prediction
      ↓
Evaluation (MAE + R²)
      ↓
Visualization
```

---

## 📊 Features Used

| Feature | Description | Type |
|---------|-------------|------|
| `Hours_Studied` | Number of hours studied per week | Numerical |
| `Attendance_Percentage` | Student attendance (%) | Numerical |
| `Previous_Score` | Score in previous assessment | Numerical |

**Label (Target):** `Score` — Final exam score to predict

---

## 🤖 Model Used

**Linear Regression** from Scikit-learn

- Finds the best linear relationship between features and the target
- Formula: `Score = (c1 × Hours_Studied) + (c2 × Attendance) + (c3 × Previous_Score) + intercept`
- Fast, interpretable, and effective for this dataset

---

## 📈 Evaluation Metrics

| Metric | Description | Ideal Value |
|--------|-------------|-------------|
| **MAE** (Mean Absolute Error) | Average prediction error in score points | As low as possible |
| **R² Score** | How much variance is explained by the model | Close to 1.0 |

---

## 📉 Visualizations

The notebook includes **5 interactive Plotly visualizations**:

1. **Scatter Plot** — Hours Studied vs Score
2. **Scatter Plot** — Attendance Percentage vs Score
3. **Scatter Plot** — Previous Score vs Score
4. **Histogram** — Score Distribution
5. **Correlation Heatmap** — Feature correlations

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/week3-day1-ml-fundamentals.git
cd week3-day1-ml-fundamentals
```

### 2. Install Required Libraries
```bash
pip install pandas numpy scikit-learn plotly jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook assignment.ipynb
```

### 4. Run All Cells
- Go to **Kernel → Restart & Run All**
- All outputs, plots, and predictions will be generated automatically

---

## ✅ Expected Output

After running the notebook, you should see:

- Dataset preview with 110 rows and 4 columns
- Training set: ~88 samples | Test set: ~22 samples
- Model coefficients for each feature
- Predicted scores for Student A, B, and C
- MAE around 1–3 points
- R² Score above 0.95
- 5 interactive Plotly charts

---

## 🎓 Learning Outcomes

After completing this project, you will be able to:

- ✅ Explain what Machine Learning is and how it works
- ✅ Distinguish between features and labels
- ✅ Perform exploratory data analysis (EDA)
- ✅ Apply train-test split correctly
- ✅ Train and evaluate a Linear Regression model
- ✅ Interpret MAE and R² Score
- ✅ Create interactive visualizations with Plotly
- ✅ Make predictions for new data points

---

## 👤 Author

SHAIK ASMA SIDDIQUA
- AIML Internship — Week 3, Day 1
- GitHub: [@logicCrafts786](https://github.com/logicCrafts786)

---

## 📝 License

This project is created for educational purposes as part of an internship assignment.

---

*Built with ❤️ during AIML Internship Program*
