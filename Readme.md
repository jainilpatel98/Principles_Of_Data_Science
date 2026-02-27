
# Principle of Data Science – Assignments

This repository contains my coursework for **Principle of Data Science**.

## Repository Structure

```text
PrincipleOfDataScienceAssignments/
├─ Assignment_1/
│  ├─ Question1/
│  ├─ Question2/
│  ├─ Assignment 1.docx
│  ├─ README.md
│  └─ requirements.txt
├─ .venv/                  # local Python virtual environment (not committed)
└─ Readme.md               # (this file) repo-level overview
```

## Quick Start

### 1) Create / activate the virtual environment

From the repository root:

```bash
python -m venv .venv
source .venv/bin/activate        # macOS/Linux
# .venv\Scripts\activate         # Windows PowerShell
```

### 2) Install dependencies

If you are working on a specific assignment, install that assignment’s requirements:

```bash
pip install -r Assignment_1/requirements.txt
```

### 3) Run notebooks / scripts

Open the notebooks from the relevant assignment folder (e.g., `Assignment_1/Question1/` or `Assignment_1/Question2/`) using Jupyter or your IDE.

```bash
python -m pip install -U jupyter
jupyter lab
```

## Assignment Notes

### Assignment 1

- **Question 1**: Data ingestion, cleaning, feature engineering, EDA + reporting.
- **Question 2**: Visualizations + short written interpretations.

See `Assignment_1/README.md` for assignment-specific instructions, assumptions, and outputs.

## Outputs

Generated artifacts are written into the assignment folders (e.g., cleaned data under `data_clean/`, reports under `reports/`, and figures under `reports/figures/`) when the assignment notebooks/scripts are executed.

## Reproducibility

- Python version: use the interpreter inside `.venv`.
- Install dependencies from the assignment `requirements.txt` before running.
