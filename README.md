# 📊 Commodity Trading Using Weather Data  

## 🌟 Overview  
This project explores the impact of weather data on commodity trading strategies, focusing on coffee—a globally significant and moderately volatile market. By integrating weather indicators with traditional technical analysis, the strategy aims to enhance trade signal accuracy and risk management.  

## 🔍 Data Sourcing & Preparation  
- **Weather Data**: Collected from Visual Crossing for Brazil, a leading coffee producer.  
- **Market Data**: Historical coffee prices aligned with weather data for consistency.  
- **Preprocessing**:  
  - Aggregated hourly weather data into daily summaries.  
  - Time-zone aligned weather and coffee market data.  
  - Created training (**Jan 2020 - Aug 2023**) and testing (**Sep 2023 - Aug 2024**) datasets.  

## 🏗️ Feature Engineering  
- **Weather Indicators**: Frost events (< 0°C), drought conditions (rainfall < 10mm/7 days), extreme rainfall (> 20mm).  
- **Technical Indicators**: Bollinger Bands, MACD, RSI, ATR for market trends and volatility.  
- **Rolling & Lagged Features**: 7-day rolling averages for temperature, humidity, and wind speed.  
- **Momentum & Trend Analysis**: Moving averages, Keltner Channels, CCI.  
- **Advanced Metrics**: VWAP for trade strength, seasonal trends.  

## 📈 Trading Strategies  
1️⃣ **Technical Indicator-Based Strategy**:  
   - Buy when **MACD > MACD Signal** and sell when **RSI > 70**.  
   - Includes leverage, stop-loss, and take-profit mechanisms.  

2️⃣ **Weather-Integrated Signal Selection**:  
   - Enhances trade signals by incorporating weather anomalies.  
   - Uses rainfall and temperature patterns for refined decision-making.  

3️⃣ **Weather-Based Position Sizing**:  
   - Adjusts trade sizes based on extreme weather conditions.  
   - Mitigates risks associated with climate-driven price fluctuations.  

## 📊 Performance Evaluation  
- Simulated **equity curves** for each strategy.  
- Measured **Sharpe, Sortino, and Calmar ratios**, along with drawdowns and win rates.  
- Results show improved strategy robustness by integrating weather data.  

## 🛠️ Tools & Technologies  
- **Python** for data processing and modeling.  
- **Pandas, NumPy** for feature engineering.  
- **Scikit-learn** for predictive analysis.  
- **Matplotlib, Seaborn** for visualization.  

🚀 This project highlights the power of alternative data sources in financial markets, demonstrating how weather insights can refine trading strategies for better risk-adjusted returns.  
