# WFM Lite — Genesys Cloud WFM Approximation

A single-page web app (no server) that approximates WFM: forecast → staffing → schedule → intraday.

- Forecast: Average or SES (alpha) with Day-of-Week seasonality
- Staffing: Erlang C + shrinkage + max occupancy; supports concurrency
- Schedule: Greedy coverage using editable shift templates
- Intraday: Upload actuals and proportional reforecast

Open `index.html` to use. See `sample_history.csv` for format.
