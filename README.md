# Student Performance — Exploratory Data Analysis (Python)

## Project Description

The **Student Performance EDA** project is a Python-based data analysis project that performs comprehensive **Exploratory Data Analysis (EDA)** on a student academic performance dataset. The objective is to identify the factors that influence student performance by analyzing **10,000 student records** across multiple academic and lifestyle variables.

This project demonstrates practical data analysis skills including **data exploration, statistical analysis, data visualization, correlation analysis, and insight generation** using **Pandas**, **NumPy**, and **Matplotlib**.

---

## Key Findings

### Overall Dataset Insights

* **10,000 student records**
* **6 features**
* **No missing values**
* **Average Performance Index: 55.2 / 100**

### Correlation with Performance Index

| Feature                          | Correlation |
| -------------------------------- | ----------- |
| Previous Scores                  | **0.92**    |
| Hours Studied                    | **0.37**    |
| Sleep Hours                      | **0.05**    |
| Sample Question Papers Practiced | **0.04**    |

### Major Findings

#### 1. Previous Scores Are the Strongest Predictor

* Correlation: **0.92**
* Students who performed well previously tend to perform well again.
* Previous academic performance is the strongest indicator of future success.

#### 2. Hours Studied Have a Moderate Impact

* Correlation: **0.37**
* Studying more generally improves performance.
* Study time contributes positively, but understanding concepts remains important.

#### 3. Extracurricular Activities Have Minimal Effect

* Students participating in extracurricular activities: **55.7 average score**
* Students not participating: **54.7 average score**
* Difference is only **1 point**, indicating very little impact on academic performance.

#### 4. Sleep Hours Show a Very Weak Relationship

* Correlation: **0.05**
* Students sleeping more tend to score slightly higher.
* Performance varies only slightly across different sleep durations.

#### 5. Sample Paper Practice Alone Is Not Enough

* Correlation: **0.04**
* Practicing sample papers without strengthening conceptual understanding has limited impact on performance.

---

## Features

* Load and explore a student performance dataset
* Verify dataset quality and completeness
* Generate descriptive statistics
* Perform univariate analysis
* Perform bivariate analysis
* Analyze correlations between variables
* Visualize distributions and relationships
* Generate educational insights and recommendations
* Identify key drivers of academic performance

---

## Concepts Used

### Python Fundamentals

* Variables and Data Types
* Conditional Statements
* Loops
* Functions
* String Formatting

### Pandas Concepts

* `read_csv()`
* `head()`
* `info()`
* `describe()`
* `shape`
* `groupby()`
* `value_counts()`
* `corr()`
* Boolean Indexing
* Statistical Aggregation

### NumPy Concepts

* Numerical Computation
* Statistical Functions
* Array Operations

### Matplotlib Concepts

* Histograms
* Bar Charts
* Scatter Plots
* Correlation Heatmaps
* Figure Customization
* Subplots
* Layout Management

### Data Analysis Concepts

* Exploratory Data Analysis (EDA)
* Univariate Analysis
* Bivariate Analysis
* Correlation Analysis
* Feature Importance Analysis
* Insight Generation

---

## Project Structure

```text
StudentPerformance-EDA/
│
├── student_performance_eda.ipynb
├── Student_Performance.csv
└── README.md
```

---

## How to Run

### Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib

### Install Required Libraries

```bash
pip install pandas numpy matplotlib
```

### Steps

1. Clone or download this repository.
2. Place `Student_Performance.csv` inside the project folder.
3. Open `student_performance_eda.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells from top to bottom.

---

## Analysis Performed

* Loaded and explored dataset structure
* Verified dataset quality and checked for missing values
* Generated descriptive statistics
* Analyzed the distribution of Performance Index
* Examined relationships between study habits and performance
* Compared performance across extracurricular activity participation
* Evaluated the effect of sleep duration on academic performance
* Analyzed sample paper practice patterns
* Calculated correlation coefficients between variables
* Identified the strongest predictors of student performance
* Generated educational recommendations based on findings

---

## Conclusions

### Factors That Affect Performance Most

#### Previous Scores (Correlation: 0.92)

Previous Scores are the strongest predictor of student performance. Students with strong academic foundations consistently achieve better results.

#### Hours Studied (Correlation: 0.37)

Study time has a moderate positive effect on performance. Consistent studying contributes to better academic outcomes.

### Factors with Little or No Effect

#### Extracurricular Activities

Participation in extracurricular activities shows almost no impact on academic performance.

#### Sleep Hours

Sleep duration has a very weak relationship with performance and only a minor influence on scores.

#### Sample Question Papers Practiced

Practicing sample papers alone does not significantly improve performance without strong conceptual understanding.

---

## Recommendations

### 1. Build Strong Academic Foundations

Since previous performance strongly predicts future performance, students should focus on mastering fundamental concepts early.

### 2. Encourage Consistent Study Habits

Regular study routines can improve academic outcomes and support long-term learning.

### 3. Prioritize Understanding Over Memorization

Students should focus on conceptual understanding rather than relying solely on practice papers.

### 4. Maintain Balanced Student Development

Extracurricular activities do not negatively affect academic performance and can be pursued alongside studies.

### 5. Follow Healthy Sleep Habits

Although sleep has a weak correlation with performance, maintaining healthy sleep patterns supports overall well-being and learning efficiency.

---

## Dataset Information

**Dataset:** Student Performance Dataset

| Attribute                 | Value             |
| ------------------------- | ----------------- |
| Rows                      | 10,000            |
| Columns                   | 6                 |
| Missing Values            | 0                 |
| Target Variable           | Performance Index |
| Average Performance Index | 55.2              |

### Features Included

* Hours Studied
* Previous Scores
* Extracurricular Activities
* Sleep Hours
* Sample Question Papers Practiced
* Performance Index

---

## Author

**Meet Tailor**
Data Science Learner

GitHub: https://github.com/MeetTailor-Data

---

## License

This project is created for learning and educational purposes only.

---

## Project Status

**Completed**

**Last Updated:** May 2026
