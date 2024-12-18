# NSE Historical Stock Price Data Analysis

A comprehensive analysis of historical stock price data from India's National Stock Exchange (NSE), focusing on correlation analysis, time series decomposition, and anomaly detection.

## Dataset

The analysis uses historical NSE stock price data on [Kaggle](https://www.kaggle.com/datasets/stacknishant/nse-stock-historical-price-data?resource=download).

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv env
```

2. Activate the virtual environment:
```bash
.\env\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

## Project Components

### 1. Data Preprocessing and Exploratory Data Analysis
- Dataset cleaning and handling of missing values/outliers
- Statistical analysis of stock prices and volumes
- Visualization of price trends for top 10 stocks

### 2. Correlation Analysis
- Development of stock returns correlation matrix
- Identification of highly correlated stock pairs
- Visual representation using correlation heatmaps

### 3. Time Series Decomposition
- Single stock time series analysis
- Components identification: trend, seasonality, residuals
- Trading implications analysis

### 4. Anomaly Detection
- Implementation of price movement anomaly detection
- Analysis of top 5 significant anomalies
- Investigation of anomaly causes

## Key Findings

### Correlation Analysis Results

#### Positive Correlations
1. **Strong Banking Sector Correlations:**
   - ICICIBANK & SBIN: 0.53 correlation
   - ICICIBANK & HDFCBANK: 0.44 correlation
2. **Cross-Sector Correlations:**
   - RELIANCE & SBIN: 0.39 correlation
   - SBIN & ITC: 0.37 correlation

#### Portfolio Implications
- **Diversification Opportunities:**
  - Include LICI or INFY for risk reduction
  - Consider international investments
- **Sector-Specific Insights:**
  - Strong banking sector interconnections
  - Moderate correlations in consumer goods and IT sectors

### Anomaly Detection Results

Analysis of RELIANCE stock price anomalies:

1. **June 9, 2022 (₹2583.25)**
   - Requires investigation of news events
   - Analysis of industry trends

2. **August 14, 2023 (₹2577.25)**
   - Market conditions analysis
   - Company-specific factor review

3. **June 3, 2022 (₹2565.48)**
   - Technical analysis review
   - Market sentiment assessment

4. **June 7, 2022 (₹2559.25)**
   - Trading activity analysis
   - Market volatility review

5. **June 6, 2022 (₹2554.45)**
   - Sector performance comparison
   - Investor behavior analysis

## Future Work
- Implementation of real-time anomaly detection
- Development of trading strategies based on correlation insights
- Integration of additional market indicators
- Extension of analysis to more stocks and longer time periods

## Contributing
Feel free to submit pull requests. For major changes, please open an issue first to discuss the proposed changes.
