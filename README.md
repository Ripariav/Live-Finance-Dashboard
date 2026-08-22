# Live Finance Dashboard

![Python](https://img.shields.io/badge/Python-3-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Backend-000000?logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly--Dash-Interactive%20Charts-3F4F75?logo=plotly&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-Live%20Data-green)

Interactive dashboard built with **Flask** and **Plotly Dash**,
visualizing real-time financial data pulled from Yahoo Finance via
`yfinance`. Lets you pick a stock ticker and a date range, and shows
price history, daily change and volatility on interactive charts.

---

## Stack

- **Flask** — main server, routing
- **Dash (Plotly)** — embedded inside Flask for the interactive dashboard
- **yfinance** — real-time and historical stock data
- **pandas / numpy** — data processing

---

## Running locally

```bash
pip install -r requirements.txt
python main.py
```

The dashboard is served through the Flask app and is reachable at
`http://localhost:5000` by default.

---

## License

MIT
