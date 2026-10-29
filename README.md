# CM2604 Machine Learning — Telco Customer Churn

## Files
- `CM2604_Telco_Churn_ML_Coursework.ipynb`: full EDA, preprocessing, tuning, evaluation, and ethics workflow.
- `CM2604_Report_Scaffold.docx`: report structure with placeholders to replace using actual experimental results.

## Run
1. Open the notebook in Google Colab or Jupyter.
2. Upload the Telco Customer Churn CSV when prompted.
3. Run all cells from top to bottom.
4. Review the generated charts and CSV result tables.
5. Replace every placeholder in the report with your actual results and source details.

## Reproducibility
The notebook uses random seed 42, an 80/20 stratified train/test split, and stratified 5-fold cross-validation. Preprocessing is inside the pipeline to reduce leakage. Hyperparameters are selected on training folds; the test set is reserved for final evaluation.

## Dataset
Use the Telco Customer Churn dataset specified by the coursework. Record the exact source URL, access date, version, and license in your report. Do not commit private data or credentials.
