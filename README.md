# Rainfall Analysis and Planting Advisory

This project uses NumPy to clean monthly rainfall readings, compare annual and monthly rainfall across five Kenyan counties, and identify the strongest two-month planting windows.

## How to run

Open `rainfall_analysis.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab, install the packages listed in `requirements.txt`, then run all cells from top to bottom. The analysis writes `rainfall_summary.csv` to the notebook's working directory.

## Planting Advisory

- Nairobi and Nakuru have their strongest consecutive rainfall in April–May, so farmers can use this as a provisional planting window while checking local forecasts.
- Kisumu and Mombasa also peak across April–May; prepare fields ahead of the long rains and adjust planting to local soil moisture.
- Machakos has its strongest adjacent-month total in November–December, but its readings include two average-imputed months, so verify station data and current forecasts before acting.
