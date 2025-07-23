# 🎓 Student Performance Analysis

This project explores student exam performance based on various demographic and educational factors. Using Python (Pandas) for **Exploratory Data Analysis (EDA)** and **Power BI** for data visualization, this project uncovers key insights into what impacts student outcomes.

---

## 📂 Dataset

* **Source:** [Kaggle - Student Performance Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
* **Columns:**

  * `gender`
  * `race/ethnicity`
  * `parental level of education`
  * `lunch`
  * `test preparation course`
  * `math score`
  * `reading score`
  * `writing score`

---

## 🎯 Objectives

* Perform detailed EDA using Pandas.
* Answer tricky and meaningful business questions.
* Create an interactive Power BI dashboard to showcase findings.
* Categorize students into performance categories using logic.

---

## 🧠 Key EDA Questions Answered

1. Which **parental education level** is linked with the highest average math score?
2. Is there a significant **gender-based performance** difference across all subjects?
3. How does **test preparation course completion** affect subject-wise scores?
4. Which **combination of gender, lunch, and test-prep status** produces top performers?
5. Does **lunch type** have uniform effects across **ethnic groups**, or does it vary?
6. What is the correlation between **reading vs. writing** and **math vs. writing**?
7. Who are the **top 5% performers** and what demographic patterns are visible?
8. Can we cluster students into **low/medium/high performance categories** using Pandas?

---

## 📊 Power BI Dashboard Highlights

* **Visuals Used:**

  * Bar Charts (Performance by score & category)
  * Box Plot (Score distribution by category)
  * KPI Cards (Average math, reading, writing, total score)
  * Correlation Heatmap
* **Filters (Slicers):**

  * Gender
  * Lunch Type
  * Test Preparation Course
* **Performance Categories:**

  * Defined using total score thresholds (Low, Medium, High)

---

## 🗂️ Project Files

| File                                                    | Description                                        |
| ------------------------------------------------------- | -------------------------------------------------- |
| `ZuhaIsmail_StudentPerformanceAnalysis_project03.ipynb` | Python notebook with full EDA and logic            |
| `SPA_PowerBI_Dashboard_Image.png`                       | Image preview of the Power BI dashboard            |
| `StudentPerformanceAnalysis_Dashboard.pbix`             | Power BI interactive dashboard                     |
| `cleaned_student_performance.csv`                       | Cleaned version of the dataset used in analysis    |
| `README.md`                                             | GitHub project description file                    |


---

## 🛠️ Tools & Libraries Used

* **Python:** `pandas`, `matplotlib`, `seaborn`, `numpy`
* **Visualization:** Power BI
* **Notebook Environment:** Google Colab

---

## 📈 Key Insights

* Test preparation significantly boosts student performance.
* Female students scored higher in reading and writing; males performed slightly better in math.
* Students with standard lunch generally performed better.
* Strong correlation exists between reading and writing scores.

---

## 🚀 How to Run

1. Download the dataset from Kaggle.
2. Open the provided Colab or Jupyter Notebook and run all cells.
3. Open the `.pbix` file in Power BI Desktop to explore the interactive dashboard.

---

## 📧 Contact

For queries, suggestions, or collaborations, feel free to connect!

