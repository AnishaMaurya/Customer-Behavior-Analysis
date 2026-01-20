# Customer Behavior Analysis

Project analyzing customer shopping behavior using exploratory data analysis and basic modeling.

Overview
--------
This repository contains an exploratory analysis of customer shopping behavior based on transactional and demographic data. The goal is to understand patterns, visualize trends, and derive actionable insights for marketing and product teams.

Dataset
-------
The dataset used is `customer_shopping_behavior.csv`. It includes features such as customer demographics, transaction amounts, product categories, and timestamps. See the notebook for details on columns and preprocessing steps.

Files
-----
- `customer_shopping_behavior.csv` — raw data (CSV).
- `Exploratory_Data_Analysis.ipynb` — Jupyter notebook with data cleaning, analysis, visualizations, and initial modeling.

Getting started
---------------
Recommended Python environment and dependencies (common packages used in the notebook):

```bash
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
pip install --upgrade pip
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

If you prefer `conda`:

```bash
conda create -n customer-behavior python=3.10 -y
conda activate customer-behavior
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Usage
-----
Open and run the notebook to reproduce the analysis and plots:

```bash
jupyter notebook Exploratory_Data_Analysis.ipynb
```

Key steps in the notebook
------------------------
- Data loading and initial inspection
- Data cleaning and feature engineering
- Exploratory visualizations (distributions, correlations, time-based trends)
- Simple predictive modeling (baseline classifiers/regressors) and evaluation

Results
-------
See the notebook for visualizations and a short summary of findings. Typical outcomes include customer segments, high-value product categories, and suggested next steps for targeted marketing.

Contributing
------------
If you'd like to contribute, please open an issue or submit a pull request with a clear description of proposed changes.

License
-------
This project is provided as-is for analysis and learning purposes. Add a license file if you intend to publish or share broadly.

Contact
-------
For questions, reach out to the repository owner.