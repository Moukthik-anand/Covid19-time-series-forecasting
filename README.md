# COVID-19 Time Series Forecasting using Facebook Prophet

## Overview
This project focuses on analyzing and forecasting global COVID-19 confirmed cases using time series analysis. Historical COVID-19 data is preprocessed and aggregated on a daily basis, and Facebook Prophet is used to model trends and predict future confirmed cases.

The project demonstrates how time-series forecasting can be applied to real-world pandemic data for understanding trends and estimating future case counts.

---

## Dataset
- Format: CSV
- Data includes:
  - Date
  - Country/Region
  - Confirmed cases
  - Deaths
  - Recovered cases
  - Active cases
- Data is grouped globally by date for forecasting.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Facebook Prophet
- Google Colab / Jupyter Notebook

---

## Methodology
1. Load COVID-19 dataset using Pandas.
2. Perform data preprocessing and column renaming.
3. Aggregate confirmed cases on a daily basis.
4. Prepare data in Prophet-compatible format (`ds`, `y`).
5. Train Facebook Prophet time series model.
6. Generate future dates and forecast confirmed cases.
7. Visualize historical data and future predictions.

---

## Results
- The model forecasts global confirmed COVID-19 cases for the next 21 days.
- Predictions include:
  - Estimated values (`yhat`)
  - Lower bound (`yhat_lower`)
  - Upper bound (`yhat_upper`)
- Forecast trends are visualized using Prophet’s built-in plotting tools.

---

## Future Scope
- Apply ARIMA and SARIMA models for comparison.
- Country-specific forecasting.
- Interactive dashboards using Plotly or Streamlit.
- Inclusion of vaccination and testing datasets.

---

## How to Run
1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Install required libraries.
4. Run all cells sequentially.

---

## Author
M.Moukthik Anand