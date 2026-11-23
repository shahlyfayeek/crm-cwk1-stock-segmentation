# crm-cwk1-stock-segmentation

6BUIS017W CRM & CM with Business Intelligence, CWK1: Market analysis and stock segmentation using RFM on S and P 500 shares.

IIT ID 20231076 | UoW ID 20521398

## Contents

- `CRM_CWK1_20521398.ipynb`: the full coursework notebook (Tasks 1, 2 and 3), runnable in Google Colab.
- `data/`: the static dataset and every output the notebook produces.
  - Raw snapshots: `raw_adj_close.csv.gz`, `raw_close.csv.gz`, `raw_volume.csv.gz`, `sp500_constituents.csv`
  - Validation logs: `exclusion_log.csv`, `validation_checks.txt`, `download_failures.csv`, `corporate_action_flags.csv`, `splits_found.csv`
  - Features: `feature_table.csv`, `recency.csv`, `frequency.csv`, `monetary.csv`, `weekly_beta.csv`, `mean_weekly_return.csv`, `weekly_returns.csv.gz`
  - Clustering outputs: standardised matrices, k comparison tables, `cluster_assignments.csv`, cluster profiles, correlations and sector composition tables
- `figures/`: all figures used in the report.
- `package_versions.txt`: package versions used.

## How to run

Open the notebook in Colab and choose Runtime > Run all. With `USE_SNAPSHOT = True` (the default) it loads the fixed dataset from `data/`, so the results are reproducible and no live download is needed.
