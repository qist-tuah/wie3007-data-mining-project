# WIE3007 Data Mining - Group Project

## Team
| Member | Role | Model(s) |
|---|---|---|
| Muaz Zikry Bin Samsul | Dataset Simulation | Decision Tree (baseline) |
| Muhammad Adam Harith Bin Mohd Zaki | LLM Feature Engineering + EDA | Logistic Regression |
| Qistina Aqilah Binti Abdul Razak Tuah | Ensemble Models + Interpretation | Random Forest, XGBoost |
| Muhammad Aliff Adam Bin Sultan | Neural Network + Evaluation | MLP |

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
