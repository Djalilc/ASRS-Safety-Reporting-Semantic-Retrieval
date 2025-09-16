# ASRS Safety Reporting Semantic Retrieval

This project analyzes the NASA-ASRS Aviation Safety Reporting dataset and explores semantic retrieval methods for incident reports.  
It begins with exploratory data analysis (EDA) and progresses toward building hybrid rule-based and transformer-based retrieval pipelines.

## Repository Structure
- `notebooks/` → Jupyter notebooks with full analysis  
- `src/` → Utility scripts (if needed)  
- `data/` → Dataset instructions (not raw data)  
- `requirements.txt` → Dependencies  
- `README.md` → Project overview

## Installation
```bash
git clone https://github.com/your-username/ASRS-Safety-Reporting-Semantic-Retrieval.git
cd ASRS-Safety-Reporting-Semantic-Retrieval
pip install -r requirements.txt
```

## Usage
Open the notebook:
```bash
jupyter notebook notebooks/asrs_safety_reporting_semantic_retrieval.ipynb
```

## Results and Insights
- Distribution of report types and sources  
- Common categories of safety incidents  
- Preliminary clustering of text data  
- Visualizations of time trends  

## Future Work
- Apply NLP models (SBERT / Transformers) for semantic clustering  
- Build incident risk prediction baseline  
- Explore hybrid rule-based + ML validation  
