# Currency Tracker INR/CAD

A minimalist black & white currency tracker with live rates, historical charts, and hourly forecast (Dec 24, 2024 – Jan 12, 2025) using realistic statistical modeling and exponential smoothing.

## Project Structure

```currencytracker-inr-cad/
├── public/                     
│   └── index.html              # HTML template and static assets
│
├── src/
│   ├── components/             
│   │   ├── currency/
│   │   │   ├── CurrencyConverter.jsx   # Convert INR ↔ CAD
│   │   │   ├── ForecastChart.jsx       # Hourly forecast chart
│   │   │   ├── HistoricalChart.jsx    # Historical rates chart
│   │   │   ├── RateDisplay.jsx        # Current rate display
│   │   │   └── StatsPanel.jsx         # Statistics panel for historical data
│   │   └── Home.jsx                    # Main homepage component with tabs
│   │
│   ├── hooks/                          # Custom React hooks (if any)
│   │
│   ├── utils/                          # Utility functions
│   │   └── forecastUtils.js            # Data generation & forecast functions
│   │
│   ├── App.jsx                         # Main React app component
│   └── index.jsx                        # ReactDOM render and global imports
│
├── package.json                         # Project dependencies & scripts
├── package-lock.json                    # Exact dependency versions
├── README.md                            # Project overview & structure
└── .gitignore                           # Files/folders to ignore in git
```

## Features

- Live INR ↔ CAD exchange rate
- Historical data visualization
- Hourly forecast (Dec 24, 2024 – Jan 12, 2025)
- Minimalist black & white UI
- Responsive layout for desktop and mobile

## Getting Started

1. Clone the repository:

```git clone https://github.com/<your-username>/currencytracker-inr-cad.git```
