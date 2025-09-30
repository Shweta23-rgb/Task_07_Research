# Task_07_Research

This repository contains the full workflow and report for Task 07: Decision-Making with Women’s Happiness Data (2021). The goal is to analyze global women’s happiness scores, validate descriptive findings, quantify uncertainty, and provide tiered policy recommendations for stakeholders such as the UN, NGOs, and national policy advisors.

Task_07_Research/
│
├── data/
│   └── merged_happiness_data.csv      # Cleaned dataset (125 countries, 11 features)
│
├── notebooks/
│   └── Womens_Happiness_2021.ipynb    # Main analysis notebook (EDA, uncertainty, sanity checks)
│
├── prompts/
│   ├── narrative_prompts.txt          # All prompts given to the LLM
│   └── raw_llm_output.md              # Exact LLM responses before editing
│
├── report/
│   ├── Decision_Report.md             # Final stakeholder report
│   └── figures/                       # Saved figures used in the report
│       ├── correlation_matrix.png
│       ├── regional_boxplot.png
│       ├── robustness_check.png
│       └── uncertainty_ci.png
│
└── README.md                          # Repository overview (this file)

Contents

Dataset: Combined from the 2021 World Happiness Report, 2021 Women’s Happiness Report, and map subregion codes (via Kaggle).

Notebook: End-to-end workflow including data cleaning, EDA, uncertainty checks, fairness checks, and robustness analysis.

Prompts & Outputs: Full LLM transcript with ground truth validation for reproducibility.

Report: Policy-facing decision report with recommendations labeled by risk level (operational, investigatory, high-stakes).
