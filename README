# 🧬 Biodefense: Epidemic Simulation & Risk Analysis

This repository contains a 3-part analysis pipeline simulating a disease outbreak across the UK and performing spatial and demographic analysis on infection data.

These notebooks were developed as part of a hands-on project inspired by an AWS Deep Learning Institute (DLI) lab.

⚠️ **Note:** The dataset used in this project is hosted in a restricted S3 bucket (`s3://dli-lms/...`) and is not publicly available. Code is provided for learning purposes.

---

## 📁 Notebooks

### 🔹 Week 1 – `find_infected.ipynb`
Simulates the progression of infections over multiple days using predefined infection spread models.

- Reads per-day population and infection data.
- Tracks new and cumulative infections.
- Outputs infection heatmaps and regional infection growth.

### 🔹 Week 2 – `nearest_facilities.ipynb`
Performs spatial analysis to link infected zones with nearby healthcare facilities.

- Loads geospatial boundary and hospital/clinic data.
- Uses KDTree for nearest-neighbor search.
- Visualizes clusters and emergency proximity on a map.

### 🔹 Week 3 – `identify_risk_factors.ipynb`
Identifies which demographic factors contribute most to infection severity.

- Merges population data with infection records.
- Applies logistic regression using RAPIDS cuML.
- Outputs key risk predictors (e.g., age, employment status, chronic illness).

---

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- RAPIDS: `cuDF`, `cuML`, `cuGraph`
- Scikit-learn
- Geospatial: `geopandas`, `shapely`, `scipy.spatial.KDTree`
- Visualization: `plotly`, `matplotlib`

---

## 📦 Installation

```bash
pip install -r requirements.txt
