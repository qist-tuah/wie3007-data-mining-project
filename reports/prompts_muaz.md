# AI Usage Log – Dataset Simulation (Muaz Zikry)

## Prompt 1 – Loan dataset generation
- **Date:** 20 Nov 2026
- **Tool / model:** Claude Sonnet 5.5
- **Purpose:** Generate synthetic bank loan records (100 per batch)
- **Prompt:**

```
Generate 100 realistic synthetic bank loan customer records as CSV (no markdown, header row only once).
Columns: customer_id (start at C{START}), age (21-65), annual_income (RM, 24000-300000),
loan_amount (RM, 5000-500000), loan_term_months (12-360), credit_score (300-850),
existing_debts (RM, 0-200000), employment_years (0-40),
employment_type (Salaried/Self-employed/Contract/Unemployed),
region (Klang Valley/Penang/Johor/Sabah/Sarawak/Other),
loan_purpose (Home/Car/Education/Business/Personal),
customer_feedback (1-3 sentences in the customer's own voice about their finances or the loan, varied tone and wording),
default (0 or 1).
Rules: about 22% of rows have default=1. Default should be more likely with low credit_score,
high existing_debts relative to income, short employment_years, or unemployed/contract status,
but not perfectly predictable. Feedback tone should loosely (not strictly) match financial stress.
Values must be varied and realistic, with no repeated feedback sentences.
```

- **Notes:** [e.g. changed {START} per batch; output saved to data/raw/batches/]

## Prompt 2 – (add any prompt changes or fixes here)
- **Date:**
- **Tool / model:**
- **Purpose:**
- **Prompt:**
- **Notes:**