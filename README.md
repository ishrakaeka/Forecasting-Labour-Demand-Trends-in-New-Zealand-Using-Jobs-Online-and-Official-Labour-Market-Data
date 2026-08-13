# Forecasting-Labour-Demand-Trends-in-New-Zealand-Using-Jobs-Online-and-Official-Labour-Market-Data

Project Overview:
This project analyses short-term labour demand trends in New Zealand using MBIE Jobs Online and official Stats NZ labour market data.
The analysis examines changes in online job vacancies across regions, industries, occupations, and skill groups, and develops 3–6 month forecasts of labour demand.

Methodology:
Data Acquisition → Cleaning → Integration → EDA → Forecasting → Interpretation

Forecasting uses:
Prophet for trend and seasonal forecasting.
Random Forest using lagged vacancy and labour-market features.
Temporal alignment of monthly Jobs Online and quarterly Stats NZ data.
Lag features to reduce temporal leakage.

Key Findings:
Online labour demand changes significantly over time, reflecting economic disruptions and recovery periods.
Labour demand varies substantially across regions, industries, and occupations.
Jobs Online provides a useful signal for 3–6 month short-term forecasting.
Stats NZ employment, unemployment, and underutilisation indicators provide important context for interpreting vacancy trends.
Combining vacancy and official labour-market data provides a more complete view of New Zealand's labour market.

Technologies:
Python · Pandas · NumPy · Matplotlib · Scikit-learn · Prophet · Jupyter Notebook · Streamlit

Limitations:
Jobs Online represents online job advertisements rather than total labour demand. Differences in data frequency required interpolation/alignment, and subgroup forecasts can be more sensitive to short-term fluctuations.

Conclusion:
The project demonstrates that Jobs Online can support short-term labour demand monitoring and forecasting, while Stats NZ data provides valuable economic context. The combined approach helps identify how labour demand is changing across New Zealand's regions, industries, and occupations.
