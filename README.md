# CodeAlpha_Stock-Prediction

## 📈 Netflix Stock Prediction


![gif3](https://github.com/user-attachments/assets/2b9e16b4-2632-4ecb-bde2-e4d1e2cf8b59)     ![Picture0888](https://github.com/user-attachments/assets/74269138-54b8-4de3-8dd9-c43930eac577)





## 📊 Dataset Overview
The Netflix Stock Prediction dataset encompasses historical stock price data and relevant financial metrics for Netflix, Inc. This dataset is instrumental in analyzing stock performance trends, forecasting future prices, and making data-driven investment decisions.

**Key Features of the Dataset:**
- Date: The specific trading day.
- Open: The price of Netflix stock at the beginning of the trading day.
- High: The highest price Netflix stock reached during the trading day.
- Low: The lowest price Netflix stock reached during the trading day.
- Close: The price of Netflix stock at the end of the trading day.
- Volume: The number of Netflix shares traded during the day.
- Adj Close: The adjusted closing price, reflecting stock splits and dividends.

## 🧪 Exploratory Data Analysis (EDA):

EDA was conducted to uncover patterns, trends, and insights within the Netflix stock dataset:

**1. Price Movements:**

- Daily Trends: Analyzed day-to-day fluctuations in stock prices.
- Monthly & Yearly Trends: Identified long-term trends and seasonal patterns.

**2. Volume Trends:**

- Studied the trading volume variations and their correlation with price movements.

**3. Moving Averages:**

- Calculated 20-day, 50-day, and 200-day moving averages to smooth out short-term price fluctuations and identify long-term trends.

**4. Correlation Analysis:**

- Investigated relationships between different stock attributes (Open, High, Low, Close, Volume) to understand interdependencies.

**5. Seasonality:**

- Explored seasonal trends affecting stock performance, such as earnings reports and major content releases.

**6. Price Distribution:**

- Analyzed the distribution of closing prices to understand the stock's volatility and performance consistency.

## 🚀 Key Features :

**1. Python Analysis**

Delve into the Python code to discover the transformations, data manipulations, and predictive analyses applied to the Netflix stock dataset. Key processes include:

- Data Cleaning: Handling missing values, outliers, and ensuring data consistency.
- Feature Engineering: Creating new features like moving averages, volatility indicators, and lagged variables to enhance model performance.
- Normalization: Scaling data using MinMaxScaler for efficient model training.
  
**2. Predictive Modeling**

Implemented various machine learning and deep learning models to forecast Netflix stock prices:

- Linear Regression: Established a baseline for predictive performance.
- Random Forest Regressor: Captured non-linear relationships in the data.
- Support Vector Machine (SVM): Utilized for regression tasks with high-dimensional data.
- XGBoost: Leveraged for its robustness and performance in structured data.
- LSTM & GRU: Employed deep learning models to capture temporal dependencies and sequential patterns in stock prices.
  
**3. Visualization and Dashboard**

Created an interactive dashboard using Dash and Plotly to visualize stock data, predictions, and insights in real-time:

- Candlestick Chart: Visualizes Open, High, Low, and Close prices for comprehensive stock movement analysis.
- Volume Prediction: Displays predicted trading volumes alongside historical data.
- Moving Averages: Shows different moving averages to identify trend directions.
- Animated Plots: Incorporates animations to dynamically illustrate stock performance over time.
- Interactive Filters: Allows users to customize views based on date ranges, stock attributes, and moving average windows.

**4. Model Performance Metrics**

Evaluated model performance using various metrics to ensure accuracy and reliability:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R²)
  
**5. Hyperparameter Tuning**

Optimized model parameters to enhance predictive performance through:

- Grid Search: Systematically explored hyperparameter combinations.
- Random Search: Randomly sampled hyperparameter space for efficiency.
- Early Stopping: Prevented overfitting by halting training when validation performance ceased to improve.

**6. Feature Importance**

Analyzed feature importance to understand which variables most significantly impact stock price predictions, providing actionable insights for investment strategies.

## 📊 Dashboard Preview :

- Candlestick Chart: Analyze daily stock movements with Open, High, Low, and Close prices.
- Volume Trends: View historical and predicted trading volumes.
- Moving Averages: Customize moving average windows to identify trends.
- Interactive Filters: Adjust date ranges and stock attributes for tailored insights.
- Animated Visuals: Watch dynamic plots illustrating stock performance over time.

## 🧰 Tools Used

- Python: Core programming language for data analysis and modeling.
- Pandas: Data manipulation and analysis.
- NumPy: Numerical computations.
- Matplotlib & Seaborn: Data visualization.
- Plotly & Dash: Interactive plotting and dashboard creation.
- Scikit-learn: Machine learning algorithms and tools.
- XGBoost: Gradient boosting framework for optimal performance.
- Keras & TensorFlow: Deep learning frameworks for LSTM and GRU models.

## 💡 Insights

- Market Leaders: Netflix’s stock exhibits strong performance trends, often leading in streaming sector movements.
- Volatility Patterns: Identified periods of high volatility correlating with major content releases and earnings reports.
- Volume Correlations: Trading volume spikes are closely linked with significant price movements, indicating strong investor interest.
- Moving Averages: 50-day and 200-day moving averages effectively signal trend reversals and momentum shifts.
- Model Performance: LSTM and GRU models outperform traditional machine learning models in capturing temporal dependencies and providing accurate forecasts.

## 📈 Key Insights

- Trend Identification: Netflix's stock shows consistent upward momentum during expansion phases, with occasional corrections aligning with broader market downturns.
- Volume Analysis: Increased trading volumes often precede significant price movements, serving as potential indicators for investment decisions.
- Moving Averages Utility: Moving averages serve as reliable indicators for long-term trend analysis, aiding in the identification of buy and sell signals.
- Model Accuracy: Deep learning models (LSTM & GRU) provide superior predictive accuracy compared to traditional models, effectively capturing the complexities of stock price movements.
- Seasonal Patterns: Certain times of the year, such as earnings seasons and major content releases, consistently influence stock performance.

## 🛠️ Setup and Usage 

**1. Clone the Repository**
```bash
    https://github.com/Sameer8750/SCT_TrackCode_01.git
```

**2. Install Dependencies**

Ensure you have Python installed. Install the required packages using pip:
```bash
    pip install pandas numpy matplotlib seaborn plotly dash dash-bootstrap-components scikit-learn xgboost tensorflow keras
```

**3. Data Preparation**

Ensure the Netflix stock dataset (Netflix.csv) is placed in the data/ directory. The dataset should include columns: Date, Open, High, Low, Close, Volume, and Adj Close.

## 🤝 Contributing

Contributions are welcome! Whether you want to enhance the analysis, improve the dashboard, or add new features, your input is valuable.

**Guidelines:**

- Follow the existing code style and documentation standards.
- Ensure that any new features include relevant tests.
- Provide clear and concise commit messages.
- Update the documentation to reflect your changes.

## 📬 Contact

Feel free to reach out for any queries, suggestions, or collaborations:

- Sameer Shinde
- Email: sameershinde1621@gmail.com
