# Assignment 1 Submission Structure

This project is organized into two question folders as requested.
This project is ran in python 3.13.3 in the computer. It can be ran on the colab too. 
## Folder Structure

```
.
├── Question1/
│   ├── data_raw/
│   │   └── frailty_raw.csv
│   ├── data_clean/
│   │   └── frailty_processed.csv
│   ├── src/
│   │   └── Q1_Frailty_Workflow.ipynb
│   └── reports/
│       └── findings.md
├── Question2/
│   ├── data_raw/
│   │   └── StudentsPerformance.csv
│   ├── data_clean/
│   │   └── students_performance_clean.csv
│   ├── src/
│   │   └── Q2_Student_Performance_Visualizations.ipynb
│   └── reports/
│       ├── visualization_interpretations.md
│       └── figures/
│           ├── v1_gender_boxplots.png
│           ├── v2_test_prep_math.png
│           ├── v3_lunch_average_performance.png
│           ├── v4_subject_correlations.png
│           └── v5_math_vs_reading_trendlines.png
└── requirements.txt
```

## How to Run

1. Install dependencies:
   ```bash
   cd /path/to/Assignment_1
   pip install -r requirements.txt
   ```
2. Run Question 1 notebook from `Question1/src/`.
3. Run Question 2 notebook from `Question2/src/`.

Both notebooks are self-contained relative to their own question folder structure.
