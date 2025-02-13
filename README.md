# Conclusion:

### Model predictions summary

| Rank | Artist         | Exponential Smoothing | ARIMA  | Machine Learning | Blended Forecast |
|------|--------------|----------------------|--------|----------------|----------------|
| 1️  | The Killers   | 2767 min             | 1970 min | 1565 min         | **2100 min**    |
| 2️  | John Mayer   | 1461 min             | 1021 min | 1101 min         | **1194 min**    |
| 3️  | Bob Dylan    | N/A                  | 1961 min | N/A              | N/A             |
| 4️  | The Beatles  | N/A                  | N/A      | 1207 min         | N/A             |


#### Based on our dataset, we forecasted our top artist for 2025 using multiple predictive models:

- Exponential Smoothing (Time Series Smoothing)
- ARIMA (Statistical Forecasting)
- Machine Learning Regression (Random Forest)
- Blended Model (Average of all predictions)

#### Key Insights:
- The Killers consistently appear as your top predicted artist across all models.
- John Mayer is a strong contender, maintaining steady listening trends.
- Bob Dylan & The Beatles showed varying results, suggesting irregular listening patterns.
- The blended model provides a balanced forecast by averaging all approaches.
