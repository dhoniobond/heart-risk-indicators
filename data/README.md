# Data

The raw survey is too large to commit, so this folder is ignored by git.

| File | Source |
| --- | --- |
| `2015.csv` | CDC Behavioral Risk Factor Surveillance System, 2015. CSV version on [Kaggle](https://www.kaggle.com/datasets/cdc/behavioral-risk-factor-surveillance-system); original files from the [CDC](https://www.cdc.gov/brfss/annual_data/annual_2015.html). |

Running `src/heart_disease_analysis.py` writes these files here:

- `heart_disease_health_indicators2014.csv`: the cleaned 20-feature dataset
- `updated_heart_disease.csv`: state codes replaced with state names
- `heart_disease_by_state_with_coordinates.csv`: adds state coordinates for the Tableau maps
