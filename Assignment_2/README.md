# Project Structure

This folder contains the used cars and diabetes analysis project.
The work is organized with separate `data_raw`, `data_clean`, `reports`, and `src` folders inside each question directory.

## Folder Structure

```text
Assignment_2/
├── Question1/
│   ├── data_raw/
│   │   └── train.csv
│   ├── data_clean/
│   │   ├── location_price_summary.csv
│   │   ├── segment_price_summary.csv
│   │   └── used_cars_cleaned.csv
│   ├── reports/
│   │   ├── findings.md
│   │   └── figures/
│   └── src/
│       └── Q1_Used_Cars_Workflow.ipynb
├── Question2/
│   ├── data_raw/
│   │   └── diabetes.csv
│   ├── data_clean/
│   │   ├── bloodpressure_bootstrap_intervals.csv
│   │   ├── bloodpressure_bootstrap_sample_stats.csv
│   │   ├── bloodpressure_bootstrap_summary.csv
│   │   └── diabetes_sample_seed42.csv
│   ├── reports/
│   │   ├── findings.md
│   │   └── figures/
│   └── src/
│       └── Q2_Diabetes_Sampling_Bootstrap.ipynb
├── Assignment 2_3_combined.docx
├── requirements.txt
└── README.md
```

## How to Run

1. Create and activate a Python environment.
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
2. Install the required libraries.
   ```bash
   pip install -r Assignment_2/requirements.txt
   ```
3. Open Jupyter from the repository root.
   ```bash
   jupyter lab
   ```
4. Run the notebooks from:
   - `Assignment_2/Question1/src/Q1_Used_Cars_Workflow.ipynb`
   - `Assignment_2/Question2/src/Q2_Diabetes_Sampling_Bootstrap.ipynb`

## Notes

- The original datasets are stored in `data_raw/` and are not overwritten.
- The cleaned outputs and derived summaries are stored in `data_clean/`.
- The written findings are stored in `reports/findings.md`.
- The generated plots are saved in `reports/figures/`.
- The notebooks in `src/` are the main source files.
- The Python dependencies for this folder are listed in `requirements.txt`.

## What I Learned

- Cleaning a dataset is not just a technical step. The amount of missing data in a column matters when deciding whether to impute it or remove it from the working analysis.
- Converting text-based columns into usable numeric values is important before doing any meaningful statistical comparison or visualization.
- One-hot encoding makes categorical variables easier to work with, but the encoded columns become more useful when they are tied back to price trends and group summaries.
- In the used cars data, resale price is influenced by multiple factors at the same time, especially power, age, transmission type, and location.
- A small random sample can give a reasonable estimate of the population center, but it may still miss extreme values.
- Bootstrap sampling helped me understand how much a statistic can change from sample to sample, while still staying close to the overall population pattern.
- I also learned that bootstrap sampling has to be done with replacement, so repeated observations inside the same sample are expected and are actually part of the method.
- The sampling results also made the Central Limit Theorem easier to understand in practice, because the sample means stayed close to the population mean and their spread was close to what the standard error would suggest.
