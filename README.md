# WIE3007 Data Mining - Group Project

## Team
| Member | Role | Model(s) |
|---|---|---|
| Member 1 | Dataset Simulation | Decision Tree (baseline) |
| Member 2 | LLM Feature Engineering + EDA | Logistic Regression |
| Member 3 | Ensemble Models + Interpretation | Random Forest, XGBoost |
| Member 4 | Neural Network + Evaluation | MLP |

## Folder Structure
- `data/raw/` - simulated dataset
- `data/processed/` - cleaned data with LLM features
- `notebooks/` - one notebook per task
- `src/` - shared functions (preprocessing pipeline, evaluation)
- `models/` - saved models
- `figures/` - charts for the report
- `reports/` - final report

## Setup
pip install -r requirements.txt

## Workflow
1. Never push directly to `main`
2. Work on your own branch: `memberX-task`
3. Open a Pull Request to merge into `main`
4. At least 1 other member reviews before merging