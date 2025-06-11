# Employee Attrition Archetypes

This project analyzes employee attrition using the IBM HR Analytics dataset. It uses exploratory data analysis and unsupervised machine learning (KMeans clustering) to identify behavioral archetypes of employees likely to leave or stay.

##  Files

- `attrition.report.pdf` – Final project report with insights and methodology
- `attrition.codebook.ipynb` – Full code and analysis notebook (Jupyter)
- `attrition.codebook.pdf` – PDF backup of code for quick viewing
- `attrition.dashboards.pdf` – Tableau dashboards that visualize cluster findings
- PDFs are viewable after download. GitHub may not render them inline.

##  Summary

- Clustered employees into two groups using KMeans
- Used PCA for 2D visualization
- Identified factors like age, job level, and income as key attrition drivers
- Built dashboards for storytelling

##  How to Run

1. Download the dataset from Kaggle: [IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
2. Open the notebook in Jupyter or Colab
3. Install requirements:  
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
