# MedicStore Sales Analysis

This educational project uses Python and pandas to explore MedicStore sales data. The analysis is in `notebooks/Course_06_medicstore_project.ipynb`.

## Requirements

- Python 3.15 or later
- [uv](https://docs.astral.sh/uv/)
- The following files in `data/`:
  - `Sales_MedicStore_part1.csv`
  - `Sales_MedicStore_part2.csv`
  - `Mapping.xlsx`

The data files are not tracked by Git. Add them to the local `data/` directory before running the notebook.

## Setup

From the project directory, install the dependencies:

```bash
git clone git@github.com:emlyon-hids-python-2026/detaillac_course05.git
cd detaillac_course05
uv sync
```

## Run the analysis

Open `notebooks/Course_06_medicstore_project.ipynb` in VS Code, choose the project Python environment as the notebook kernel, and run the cells from top to bottom. The notebook combines the sales CSV files with the category mapping, calculates sales, and explores order and country metrics.

## Excel exports

The notebook exports the merged dataset to `data/Total_Sales_MedicStore.xlsx`. It also exports the analysis table and selected results to:

- `MedicStore_Data_Analysis.xlsx`
- `line_counts.xlsx`
- `stats_summary.xlsx`
- `sales_results.xlsx`

These four files are saved in the notebook's current working directory.

## Project structure

- `data/`: input datasets and the merged sales export
- `notebooks/`: analysis notebooks
- `scripts/`: utility scripts
- `src/detaillac_course05/`: Python package source

## Author

Constance de Taillac <constance.bartouilh@edu.em-lyon.com>
