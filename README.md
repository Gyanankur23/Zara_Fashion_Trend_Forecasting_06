# Zara_Fashion_Trend_Forecasting_06 CaseCraft Analytics Project 6

## 👗 Overview  
This project simulates Zara’s fashion sales data to forecast seasonal demand and predict trending styles. It blends time series modeling with classification to support inventory and marketing decisions.

## 🎯 Objective  
To analyze style performance across time and regions, forecast future demand using Prophet and ARIMA, and classify styles likely to trend.

## 🧵 Dataset & Features  
- 5 styles: Boho, Minimalist, Streetwear, Formal, Athleisure  
- 4 regions: North, South, East, West  
- Monthly data from Jan 2023 to Dec 2024  
- Features: units sold, price, revenue, season, region

## 📈 Visual Explorations  
- Line chart: Monthly units sold by style  
- Bar chart: Revenue by region and style  
- Boxplot: Style popularity distribution  
- Violin plot: Price distribution by style  
- Seasonal performance bar chart  
- Revenue vs units sold scatterplot

## 📊 Time Series Forecasting  
- **Prophet & ARIMA models** applied to monthly style-level sales  
- Captures seasonality and trend shifts  
- Forecasts future demand for each style

## 🤖 Classification Model  
- Target: Is a style trending (binary)  
- Features: price, revenue  
- Model: Random Forest  
- Evaluation: Confusion matrix with balanced precision and recall

## 🧠 Key Insights  
1. **Seasonal Demand**: Spring and Fall show peak sales, especially for Streetwear and Athleisure  
2. **Regional Preferences**: North and West regions drive higher revenue  
3. **Style Volatility**: Formal styles have wider price ranges, suggesting premium positioning  
4. **Trend Prediction**: Classification model identifies trending styles with reasonable accuracy  
5. **Business Utility**: Supports proactive inventory planning and targeted marketing

## ✅ Final Conclusion  
This project demonstrates how fashion retailers like Zara can leverage sales data for trend forecasting and strategic planning. By combining time series models with classification, it offers a robust framework for anticipating demand cycles and identifying high-performing styles across regions and seasons.