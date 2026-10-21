# Student Performance Analytics Engine

## 📌 Project Overview
The Student Performance Analytics Engine is a Python project that analyzes student marks using NumPy. It processes a 500 × 6 marks matrix to calculate student and subject statistics, detect outliers using Z-scores, and rank students based on their performance.

## 🎯 Objectives
- Generate a marks matrix for 500 students across 6 subjects.
- Calculate statistical measures using NumPy.
- Analyze student-wise and subject-wise performance.
- Detect unusual marks using Z-scores and broadcasting.
- Rank students based on total marks.
- Export the final results to a CSV file.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Google Colab

## ⚙️ Features

### 1. Marks Matrix Generation
Generate a 500 × 6 matrix containing marks for 500 students in 6 subjects using NumPy.

### 2. Statistical Analysis
Calculate the following measures:
- Sum
- Mean
- Median
- Standard Deviation
- Variance

Use `axis=0` for subject-wise statistics and `axis=1` for student-wise statistics.

### 3. Z-Score and Outlier Detection
Calculate Z-scores using NumPy broadcasting to identify marks that are unusually high or low compared with the subject average.

### 4. Student Ranking
Calculate each student's total marks and rank students according to their overall performance.

### 5. CSV Export
Combine student marks and total marks using `numpy.hstack()` and export the results to a CSV file.

## 📊 Project Structure

```text
Student-Performance-Analytics-Engine/
│
├── student_performance.py
├── student_marks.csv
├── student_results.csv
└── README.md
```

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new Python notebook.
3. Import NumPy and generate the 500 × 6 marks matrix.
4. Run the statistical analysis, outlier detection, and ranking code.
5. Export the results to a CSV file.

## 📈 Expected Output
- Subject-wise statistical summaries.
- Student-wise statistical summaries.
- Z-scores and outlier flags.
- Student totals and rankings.
- CSV file containing the analyzed student results.

## 💡 Learning Outcomes
- NumPy arrays and matrix operations.
- Axis-based calculations.
- Broadcasting and Z-score calculations.
- Sorting and ranking data.
- Exporting data to CSV.

## 👨‍💻 Author
**Wahid Shaikh**

GitHub: [@wahidshaikh0787-byte](https://github.com/wahidshaikh0787-byte)

---

⭐ If you find this project useful, consider giving the repository a star!

