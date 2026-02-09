# Loan Churn Analysis

This project analyzes customer churn in a short-term lending context using publicly
available loan-level data from Lending Club.

Churn is defined as **borrower inactivity**, where a loan is considered churned if
no payment activity is recorded for more than 90 days prior to a fixed reference date.
This approach focuses on behavioral disengagement rather than loan default.

This is **Version 1** of the project, focused on data analysis. Future versions will
extend this work into data engineering and cloud-based pipelines.

## Project Structure

- `notebooks/` – Data exploration and churn logic
- `data/raw/` – Raw input data (not stored in repository)
- `data/processed/` – Processed churn dataset generated locally
- `src/` – Reserved for future data engineering logic

## Data Processing

Due to file size constraints, raw and processed datasets are not stored in this repository.

To reproduce the analysis:
1. Download the Lending Club dataset from Kaggle
2. Place the raw CSV in `data/raw/`
3. Run `notebooks/01_data_exploration.ipynb`
4. The processed churn dataset will be generated in `data/processed/`

## Next Steps

- Churn rate analysis and segmentation (DA)
- SQL-based analytics layer
- Scalable ingestion and transformation pipelines (DE)
- Cloud-based storage and orchestration
