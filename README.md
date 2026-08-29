# Student Placement Data Analysis

Exploratory data analysis of student placement outcomes, academic performance, work experience, specialization, and salary using Python.

## Project Overview

This project analyzes a student placement dataset to explore the factors associated with placement outcomes and salary. The analysis examines academic performance, degree type, higher-secondary specialization, work experience, employability test scores, MBA specialization, placement status, and salary.

## Dataset

The dataset contains **215 student records** and **10 variables**:

- `gender` — Student gender
- `hsc_p` — Higher Secondary Education percentage
- `hsc_s` — Higher Secondary Education specialization
- `degree_p` — Degree percentage
- `degree_t` — Undergraduate degree type
- `work_ex` — Previous work experience
- `etest_p` — Employability test percentage
- `specialisation` — MBA specialization
- `status` — Placement status
- `salary` — Salary offered to placed students

## Analysis Workflow

The notebook covers:

- Data loading and inspection
- Data type and structure review
- Missing-value analysis
- Data preprocessing
- Descriptive statistics
- Univariate and bivariate exploratory analysis
- Outlier inspection using boxplots
- Placement-status comparisons
- Salary analysis
- Data visualization and interpretation

## Data Preprocessing

The salary column contains missing values for students who were not placed. The analysis identifies **66 missing salary entries** and handles these values by assigning a salary of `0` to students with `Not Placed` status.

## Key Findings

- Academic performance and degree specialization show important relationships with placement outcomes in the exploratory analysis.
- Commerce & Management is the most common undergraduate degree type in the dataset.
- Marketing & Finance is the more common MBA specialization compared with Marketing & HR.
- The dataset contains more placed students than non-placed students.
- Work experience is associated with differences in salary, with students who have work experience showing a higher average salary in the analyzed data.
- The analysis also explores how academic percentages, employability test performance, gender, specialization, and work experience relate to placement and salary.

## Tools & Libraries

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Repository Structure

```text
Student-Placement-Data-Analysis/
├── Placement.csv
├── Placement_Data_Analysis.ipynb
└── README.md
```

## Author

**Samaher Alsharif**

Data Science | Python | Exploratory Data Analysis
