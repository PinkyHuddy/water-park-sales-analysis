# Water Park Ticket Sales and Weather Analysis

This project explores how weather patterns affect ticket sales at a local water park.

## Summary
- Cleaned and merged daily receipts with corresponding weather data  
- Created new features (like weekday, temperature ranges, holidays, etc.)  
- Used regression models to predict daily ticket sales  
- Visualized weather impacts on revenue trends  

## Technologies
Python, pandas, matplotlib, seaborn, scikit-learn

## Setup
To install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn holidays
```

## For Recruiters
This project demonstrates:
- Data cleaning and preprocessing (merging real-world weather + sales data)
- Exploratory data analysis (visualizing trends and relationships)
- Predictive modeling (ridge regression on time-series features)
- Clear, reproducible Jupyter notebook workflow

Feel free to open the notebook in the `notebooks/` folder to view all analysis steps.

## Data Sources
- **cash_receipts.csv:** Historical ticket sales (daily totals)
- **weather.csv:** Weather data downloaded from [OpenWeatherMap](https://openweathermap.org/)