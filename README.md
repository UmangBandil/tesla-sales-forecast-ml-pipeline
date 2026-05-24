# Tesla Sales Forecast ML Pipeline

Overview
--------
This repository contains a single Jupyter notebook, [tesla_ml_pipeline.ipynb](tesla_ml_pipeline.ipynb), which implements a machine learning pipeline to forecast Tesla vehicle sales. The notebook covers data loading, exploratory data analysis, feature engineering, model training, evaluation, and simple visualization of forecast results.

Contents
--------
- Notebook: [tesla_ml_pipeline.ipynb](tesla_ml_pipeline.ipynb)

Requirements
------------
- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- Common Python packages: pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn, plotly

Install dependencies (recommended inside a virtual environment):

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install pandas numpy scikit-learn xgboost matplotlib seaborn plotly jupyter
```

Running the notebook
--------------------
1. Open the repository folder in VS Code or another editor.
2. Start Jupyter:

```bash
jupyter lab
```

3. Open [tesla_ml_pipeline.ipynb](tesla_ml_pipeline.ipynb) and run the cells sequentially. The notebook is organized to be runnable from top to bottom.

Data
----
The notebook expects any dataset files to be placed in the same directory or loaded from a specified path inside the notebook. Check the first few cells of [tesla_ml_pipeline.ipynb](tesla_ml_pipeline.ipynb) for the exact dataset filename or download instructions. If you want, I can add a `data/` folder and a sample dataset loader.

What the notebook produces
-------------------------
- Exploratory plots summarizing sales trends
- Trained forecasting models and evaluation metrics
- Forecast visualizations comparing predictions to actuals

Notes & next steps
------------------
- Consider adding a `requirements.txt` or `environment.yml` for reproducible setups.
- If you'd like, I can extract the dependency list automatically and add a `requirements.txt`.
# tesla-sales-forecast-ml-pipeline
