# currencytracker-inr-cad
React.js based live-currency tracker (hopefully with forecast visualisation) for W26 S-7 Fee payment 

currencytracker-inr-cad/
├── public/                     # Static assets like favicon, index.html
│   └── index.html
│
├── src/
│   ├── components/             # All React components
│   │   ├── currency/
│   │   │   ├── CurrencyConverter.jsx
│   │   │   ├── ForecastChart.jsx
│   │   │   ├── HistoricalChart.jsx
│   │   │   ├── RateDisplay.jsx
│   │   │   └── StatsPanel.jsx
│   │   └── Home.jsx            # Main homepage component
│   │
│   ├── hooks/                  # Optional: custom React hooks if needed
│   │
│   ├── utils/                  # Utility functions (e.g., data generation, smoothing, date handling)
│   │   └── forecastUtils.js
│   │
│   ├── App.jsx                 # Main React app entry
│   └── index.jsx               # ReactDOM render and global imports
│
├── package.json                # Project dependencies, scripts
├── package-lock.json           # Lock file for exact dependency versions
├── README.md                   # Project description & setup instructions
└── .gitignore                  # Files/folders to ignore in git
