## 🌍 Forecasting the Future: A Global Shift Towards Renewables

### 📌 Project Overview  
This project explores historical trends and future forecasts of renewable energy production (2000–2023) across 97 countries.  
Using statistical analysis, predictive modeling, and clustering techniques, we built a powerful analytical framework to evaluate global energy transition patterns and help assess progress toward 2030 renewable energy targets.

### 🎯 Objectives  
- Analyze trends in renewable vs. non-renewable energy production by region  
- Forecast 2030 energy production using Holt-Winters Exponential Smoothing  
- Compare actual and target renewable capacities for each country  
- Cluster countries based on their energy profiles: fossil-dependent, transitioning, or renewable-focused  
- Build an interactive BI dashboard for visualizing energy trends  

### 🧰 Tools and Technologies  
- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels  
- **Visualization**: Power BI Dashboard  
- **Forecasting**: Holt-Winters Exponential Smoothing  
- **Clustering**: K-Means with Silhouette, Calinski-Harabasz, and Davies-Bouldin Index validation  

### 🔬 Methodology  
- **Data Sources**:  
  - [Ember Climate Yearly Electricity Data](https://ember-energy.org/data/yearly-electricity-data/)  
  - [2030 Renewable Targets Dataset](https://ember-energy.org/data/global-renewable-power-sector-targets-2030/)  
- **Preprocessing**: Filtering, Imputation, Feature Engineering (KPI creation), and Merging  
- **Analysis**:  
  - T-Tests and ANOVA for inter-regional comparisons  
  - Pearson Correlation and Linear Regression to identify inter-renewable energy relationships  
  - Time-series forecasting (Holt-Winters)  
  - Clustering based on KPIs such as Renewable Share and Fossil Dependence  

### 📊 Key Results  
- Asia outperforms North America in solar and hydroelectric capacity  
- Solar and wind production are highly correlated (r ≈ 0.95)  
- Forecasts vary: India and USA show accurate wind power forecasts, while hydro predictions remain unstable  
- Clustering identified 3 groups: Fossil-Dependent, Transitioning, and Renewable-Focused (China stands alone in the last)  
- Interactive dashboard enables country-wise exploration of energy trends and progress toward 2030 goals  

### 🔍 Insights  
- A country’s renewable transition is deeply linked with geographic, economic, and infrastructural factors  
- Joint growth in solar and wind energy suggests shared technological and financial pathways  
- Better forecasting can be achieved using hybrid models incorporating exogenous variables (e.g., climate, policy)  


