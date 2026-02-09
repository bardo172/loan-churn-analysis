# loan-churn-analysis

This project analyzes customer churn in a short-term lending context using publicly available loan data.

Churn is defined as borrower inactivity: a customer is considered churned if they do not take a new loan within 90 days after their last loan is fully paid.

This is Version 1 of the project, focused on data analysis. Future versions will extend this work into data engineering and cloud-based pipelines.

## Data Processing

Due to file size constraints, raw and processed datasets are not stored in this repository.

To reproduce the analysis:
1. Download the Lending Club dataset from Kaggle
2. Place the raw CSV in `data/raw/`
3. Run `notebooks/01_data_exploration.ipynb`
4. The processed churn dataset will be generated in `data/processed/`
