# Sales Forecasting with Machine Learning

## 📊 Project Overview
This project predicts future sales using historical data and machine learning algorithms. It analyzes 2 years of daily sales data to identify patterns and build accurate forecasting models.

## 🎯 Objectives
- Understand sales patterns (trends, seasonality, weekly cycles)
- Build predictive models using Linear Regression and Random Forest
- Compare model performance and select the best approach
- Provide actionable insights for business planning

## 📈 Key Findings

### Sales Statistics
- **Average Daily Sales**: €1294.90
- **Total Revenue (2 years)**: €946,572.71
- **Best Performing Day**: Sunday (€1403.65)
- **Weekend Boost**: +7.5% vs weekdays

### Model Performance
**Best Model: Linear Regression**

| Model | MAE (€) | RMSE (€) | R² Score | MAPE (%) |
|-------|---------|----------|----------|----------|
| Linear Regression | 47.91 | 60.61 | 0.7178 | 3.58 |
| Random Forest | 57.86 | 72.56 | 0.5955 | 4.27 |

### Top Predictive Factors
2. sales_lag_7: 0.706
3. sales_lag_14: 0.167
5. rolling_mean_7: 0.056
1. sales_lag_1: 0.016
6. rolling_std_7: 0.015

## 🛠️ Methodology

1. **Data Generation**: Created 2 years of realistic daily sales data with trends and seasonality
2. **Exploratory Analysis**: Identified patterns by day, week, month, and quarter
3. **Feature Engineering**: Created lag features, rolling averages, and time-based features
4. **Model Training**: Trained Linear Regression and Random Forest models
5. **Evaluation**: Compared models using MAE, RMSE, R², and MAPE metrics

## 📁 Project Files

- `sales_overview.png` - Time series visualization with trends
- `sales_patterns.png` - Daily, monthly, and quarterly patterns
- `forecast_results.png` - Model predictions vs actual sales
- `feature_importance.png` - Most influential factors
- `sales_predictions.csv` - Detailed prediction results
- `processed_sales_data.csv` - Complete dataset with engineered features
- `model_comparison.csv` - Performance metrics for all models

## 💡 Business Insights

1. **Weekend Strategy**: Sales increase significantly on weekends - consider weekend promotions
2. **Seasonal Planning**: Q4 shows highest sales - prepare inventory accordingly
3. **Predictable Patterns**: Recent sales history strongly predicts future sales
4. **Special Events**: Major holidays drive significant sales spikes

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas & NumPy** - Data manipulation
- **Scikit-learn** - Machine learning models
- **Matplotlib & Seaborn** - Data visualization

## 🚀 How to Use

```python
# Run the analysis
python sales_forecasting.py
```

## 👨‍💻 About the Author

**Muhammad Faizan**

M2 Data Analytics Student | France

I'm a Master's student specializing in data analytics and machine learning, passionate about transforming data into actionable business insights. This project demonstrates my skills in time series forecasting, feature engineering, and predictive modeling.

### 🎓 Skills Demonstrated
- **Programming**: Python (Pandas, NumPy, Scikit-learn)
- **Machine Learning**: Regression models, ensemble methods, model evaluation
- **Data Visualization**: Matplotlib, Seaborn
- **Statistics**: Time series analysis, feature engineering, performance metrics
- **Business Analysis**: Translating data insights into recommendations

### 📅 Project Timeline
- **Created**: September 2025
- **Last Updated**: September 2025
- **Status**: ✅ Complete

## 📧 Contact

📩 **Email**: faizanawan579@gmail.com
💼 **LinkedIn**: [linkedin.com/in/muhammad-faizan-data](https://linkedin.com/in/muhammad-faizan-data)
🐙 **GitHub**: [github.com/mfaizan-analytics](https://github.com/faizan579)---

*This project was created as part of my data analytics internship application portfolio. I'm actively seeking opportunities in data analytics, business intelligence, and machine learning roles in France.*

**Looking for internship opportunities starting February 2026** 🚀
