# Month 1: Python & Data Handling

This month focuses on Python fundamentals, data wrangling, and habits that make you fast and reliable on client work.

## Learning Targets
- Python: data types, functions, modules, virtual environments
- Files/IO: CSV, JSON, Parquet basics
- pandas: index/loc/iloc, merge, groupby, apply
- Plotting: matplotlib basics (clear, simple visuals)
- Git hygiene: small, frequent commits with crisp messages

## Mini Projects
- **mp01_data_quality_report/**: Quick data profile + missing values summary
- **mp02_csv_to_parquet/**: CLI script to convert CSV to Parquet

## Exercises
- Short, focused tasks inside `exercises/` with a README per task.

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip wheel
pip install pandas pyarrow matplotlib jupyter scikit-learn
```

## Commit Template
Use this pattern:
```
feat: add <thing>
fix: correct <thing>
chore: update <deps or configs>
docs: improve readme or comments
```
