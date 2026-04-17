
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
├─ Assignment_2/
│  ├─ Question1/
│  ├─ Question2/
│  ├─ Assignment 2_3_combined.docx
│  └─ README.md
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

If you are working on a specific assignment, install that assignment’s requirements when available, or follow its assignment-specific README:

```bash
pip install -r Assignment_1/requirements.txt
```

For Assignment 2, see `Assignment_2/README.md` for the notebook dependencies used in that folder.

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

### Assignment 2

- **Question 1**: Used cars workflow with cleaned outputs, report figures, and source notebook.
- **Question 2**: Sampling and bootstrap workflow with saved summaries, report figures, and source notebook.

See `Assignment_2/README.md` for assignment-specific structure, assumptions, outputs, and notebook paths.

## Outputs

Generated artifacts are written into the assignment folders (e.g., cleaned data under `data_clean/`, reports under `reports/`, and figures under `reports/figures/`) when the assignment notebooks/scripts are executed.

## Reproducibility

- Python version: use the interpreter inside `.venv`.
- Install dependencies from the assignment `requirements.txt` before running.
