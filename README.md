# Classification-of-Urban-Zones-Based-on-Transport-Equity-and-Accessibility
This project classifies 41,729 urban zones across Great Britain into three accessibility categories using K-Means clustering on public transport data. By analyzing travel times to essential services (employment, healthcare, education, retail), i identified 896 priority zones with low accessibility requiring transport infrastructure investment. 
## Dataset
- Public Transport Accessibility Indicators (Great Britain, 2021)
- 446 MB, covers England, Scotland, Wales
- Measures: travel time to employment, hospitals, schools, supermarkets, GPs

## Method
1. K-Means clustering (3 groups)
2. Features: 11 travel time indicators
3. Validation: Random Forest (99.5%), XGBoost (99.7%)


## Install & Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
python analysis.py
```

## Key Finding
GP access (45 min) and supermarket access are most important for mobility equity.

## Data Source
Verduzco Torres & McArthur (2024), Zenodo
