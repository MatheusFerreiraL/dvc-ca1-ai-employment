# AI Employment in the USA: Data Visualisation (CA1)

CCT College Dublin · Data Visualisation and Communication · CA1

This repository holds a Jupyter notebook that uses visualisations to explore
employment in AI, Data Science and Software Development occupations in the USA,
based on the U.S. Bureau of Labor Statistics (BLS) Occupational Employment and
Wage Statistics (OEWS).

## Data

The data is **not** included in this repository. To run the notebook:

1. Go to https://www.bls.gov/oes/tables.htm
2. Download the "All data" file for May 2023 (`oesm23all.zip`) and the
   "National" files for May 2019 to May 2022 (`oesm19nat.zip`, `oesm20nat.zip`,
   `oesm21nat.zip`, `oesm22nat.zip`), used in the trend analysis.
3. Unzip them into the `data/` folder, keeping the original folder names,
   e.g. `data/oesm23all/all_data_M_2023.xlsx` and
   `data/oesm19nat/national_M2019_dl.xlsx`.

## How to run

Requirements: Python 3, Jupyter, pandas, openpyxl, matplotlib, seaborn, plotly
and kaleido (used by plotly to save the static copy of the map).

```bash
pip install pandas openpyxl matplotlib seaborn plotly kaleido jupyter
jupyter notebook
```

Then open the notebook and run all cells from top to bottom.
