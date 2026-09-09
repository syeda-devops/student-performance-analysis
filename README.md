# 📊 Student Performance Analysis — Task 1

### Data Science / Data Analysis with Python Internship — Main Crafts Technology

This repository contains my submission for **Task 1** of the 6-week virtual Data Science internship at **Main Crafts Technology**. The task involves analyzing the UCI Student Performance dataset using Python to uncover patterns in student academic performance.

---

## 📁 Dataset

- **Name:** Student Performance Dataset (Math course)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)
- **File used:** `student-mat.csv`
- **Size:** 395 students, 33 attributes
- **Description:** The dataset includes student demographics (age, sex, family background), academic details (study time, past grades), and social factors (family support, free time), along with final grades (G1, G2, G3).

---

## 🎯 Objective

To perform a complete data analysis workflow — **load → clean → analyze → visualize → conclude** — and answer the following questions:

1. What is the average final grade (G3) of students?
2. How many students scored above 15?
3. Is study time correlated with performance?
4. Which gender performs better on average?

---

## 🛠️ Tools & Libraries Used

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Core data visualization |
| `seaborn` | Statistical visualizations |

**Environment:** Google Colab

---

## 📅 Day-wise Progress

| Day | Stage | Notebook |
|---|---|---|
| Day 1 | Load dataset & first look | [`Day1_Data_Loading.ipynb`](notebooks/Day1_Data_Loading.ipynb) |
| Day 2 | Explore & clean data | [`Day2_Data_Cleaning.ipynb`](notebooks/Day2_Data_Cleaning.ipynb) |
| Day 3 | Answer analysis questions | [`Day3_Analysis.ipynb`](notebooks/Day3_Analysis.ipynb) |
| Day 4 | Visualizations | [`Day4_Visualizations.ipynb`](notebooks/Day4_Visualizations.ipynb) |
| Day 5 | Final report & conclusion | [`Day5_Final_Report.ipynb`](notebooks/Day5_Final_Report.ipynb) |

The final, complete notebook combining all stages is available at [`Student_Performance_Analysis_Task1.ipynb`](Student_Performance_Analysis_Task1.ipynb).

---

## 🔍 Key Findings

- ✅ The dataset was already clean — **no missing values** and **no duplicate rows**.
- 📊 The **average final grade (G3)** across all 395 students is **~10.4 out of 20**.
- 🎯 Only **40 students (~10%)** scored above 15, showing high scores are relatively rare.
- 📚 Study time shows **almost no correlation** with final grades (**r ≈ 0.098**) — meaning more study hours alone don't strongly predict better performance. Other factors like attendance, past grades, and family support likely play a bigger role.
- 👥 **Male students** scored slightly higher on average (**10.91**) than **female students** (**9.97**) — a small gap, not a strong pattern.

---

## 📈 Visualizations

| Chart | Insight |
|---|---|
| Histogram of Final Grades | Shows grade distribution is roughly bell-shaped, centered near the mean of ~10.4 |
| Scatterplot: Study Time vs Grades | Confirms weak correlation — scores vary widely at every study-time level |
| Bar Chart: Gender vs Average Grade | Shows a small performance gap between male and female students |

Chart images are available in the [`visuals/`](visuals/) folder.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/syeda-devops/student-performance-analysis.git
   ```
2. Open `Student_Performance_Analysis_Task1.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Run all cells — the dataset is loaded directly from a public URL, so no manual upload is required.

---

## 📌 Conclusion

This task walked through the complete data science workflow of loading, cleaning, analyzing, and visualizing real-world data. The key takeaway: **study time alone doesn't determine academic performance** — it's one factor among many, and data-driven analysis reveals patterns that assumptions alone can miss.

---

## 🔗 Connect

This project was completed as part of the **6-week virtual internship at Main Crafts Technology**.

#DataScience #Python #Pandas #TechInternship #MainCrafts
