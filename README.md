# AI Employment in the USA: Data Visualisation (CA1)

CCT College Dublin · Data Visualisation and Communication · CA1

This repository holds a Jupyter notebook that uses visualisations to explore
employment in AI, Data Science and Software Development occupations in the USA,
based on the U.S. Bureau of Labor Statistics (BLS) Occupational Employment and
Wage Statistics (OEWS).

## Data

The data is **not** included in this repository. To run the notebook:

1. Go to https://www.bls.gov/oes/tables.htm
2. Download the "All data" file for May 2023 (`oesm23all.zip`) and for each
   earlier year used in the trend analysis.
3. Unzip them into the `data/` folder, keeping the original folder names,
   e.g. `data/oesm23all/all_data_M_2023.xlsx`.

## How to run

Requirements: Python 3, Jupyter, pandas, openpyxl, matplotlib, seaborn, plotly.

```bash
pip install pandas openpyxl matplotlib seaborn plotly jupyter
jupyter notebook
```

Then open the notebook and run all cells from top to bottom.
