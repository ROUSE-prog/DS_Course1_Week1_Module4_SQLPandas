# SQL-Style Syntax with Pandas

This repository contains my completed **SQL-Style Syntax with Pandas** lab. The project explores how SQL-style data operations can be performed with Python and Pandas using the Titanic dataset.

## Objectives

The lab practices several approaches to querying and manipulating tabular data:

- Load and inspect data with Pandas
- Slice and filter Pandas DataFrames
- Use `DataFrame.query()` for SQL-like filtering
- Use `DataFrame.eval()` for expression-based operations
- Execute SQL queries against Pandas DataFrames with `pandasql`
- Filter, group, and aggregate Titanic passenger data
- Compare female survival outcomes across passenger classes
- Visualize query results with Matplotlib

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- pandasql
- Jupyter Notebook

## Dataset

The project uses `titanic.csv`, containing passenger information from the Titanic dataset. The notebook uses this data to practice filtering, querying, grouping, and aggregation.

## Repository Contents

- `SQLPandasLab.ipynb` — completed Jupyter Notebook containing the lab exercises
- `titanic.csv` — dataset used by the notebook

## Running the Lab

Create and activate a Python virtual environment, then install the required dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install pandas numpy matplotlib pandasql jupyter ipykernel
```

Open `SQLPandasLab.ipynb` in Jupyter or VS Code and run the notebook cells in order.

## Key Takeaway

This lab demonstrates the relationship between familiar SQL operations and their Pandas equivalents, while also showing how SQL queries can be executed directly against DataFrames using `pandasql`.
