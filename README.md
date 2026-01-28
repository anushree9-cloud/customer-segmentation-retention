# Project 1 — Customer Segmentation and Retention

Small exploratory project to perform customer segmentation and retention analysis using unsupervised and basic supervised methods. Includes data preprocessing, feature engineering, clustering, and retention/ churn analysis in a single Jupyter notebook.

## Repository structure
- project1.ipynb — main analysis notebook (preprocessing, clustering, retention analysis, visualizations)  
- README.md — this file  
- requirements.txt — Python dependencies  
- .gitignore — ignored files

## Goals
- Segment customers based on transactional and behavioral features  
- Identify high-value and at-risk cohorts  
- Derive actionable retention recommendations and simple predictive signals

## Quick start
1. Create and activate a virtual environment:
    - python -m venv .venv
    - source .venv/bin/activate (macOS/Linux) or .venv\Scripts\activate (Windows)
2. Install dependencies:
    - pip install -r requirements.txt
3. Open the notebook:
    - jupyter lab  (or jupyter notebook) and open project1.ipynb

## Data
- No raw data included. Place datasets in a `data/` folder or update paths in the notebook. Expected input: customer transactions and basic customer metadata (IDs, timestamps, amounts, demographics optional).

## Notebook highlights
- Data loading & cleaning  
- Feature engineering (recency, frequency, monetary, tenure, behavior flags)  
- Clustering (e.g., KMeans / hierarchical) and cluster profiling  
- Retention / churn cohort analysis and simple predictive checks  
- Visualizations and brief recommendations

## Notes
- Reproducibility depends on data availability and package versions in requirements.txt.  
- Adjust preprocessing steps and modeling choices to fit your dataset.

## License
- Add a license file or specify license terms as needed.