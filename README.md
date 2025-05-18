# Financial Time-Series Anomaly Detection

Hi there! 
Welcome to the Financial Time-Series Anomaly Detection project — a practical, AI-powered tool designed to help identify unusual behaviors in stock prices such as market manipulation, news-driven spikes, or rare events.

**Objective**

To detect anomalies in stock price trends and forecast future behavior using both traditional technical indicators and machine learning techniques.

**What This Project Does**

1. Loads historical stock price data (from Yahoo Finance).
2. Calculates key financial indicators (like SMA, RSI, Bollinger Bands).
3. Detects anomalies using Isolation Forest (an unsupervised machine learning model).
4. Forecasts stock price trends using Facebook Prophet.
5. Visualizes:
   - Historical price & anomalies
   - Future predictions
   - Confidence intervals

**Dataset Used**

We used an open-source Yahoo Finance Excel dataset from Kaggle with daily OHLCV data for stocks like:

- AMZN (Amazon)
- AAPL (Apple)
- TSLA (Tesla)

**Key Technologies & Libraries**

- Python
- pandas, matplotlib, seaborn — for data handling & visualization
- scikit-learn — for anomaly detection
- prophet — for time-series forecasting
- Jupyter / Kaggle Notebooks — for prototyping

**How to Run**

Step 1: Install the required packages:

```bash
pip install -r requirements.txt
```

Step 2: Open the notebook (.ipynb) and run the cells one-by-one.

All intermediate steps (data cleaning, merging, feature engineering, anomaly detection, forecasting, and visualization) are labeled with clear headings like:

- Step 1: Load and Prepare Data
- Step 2: Feature Engineering (Indicators)
- Step 3: Detect Anomalies
- Step 4: Forecast Future Trend
- Step 5: Final Visualization

**Sample Output**

You’ll see:

- Detected anomalies (red dots) overlaid on the stock price.
- A forecast line with confidence bounds (light green band).
- Prophet’s trend & seasonality decomposition.

**Author**

Made with care by an aspiring Machine Learning enthusiast (me :p). Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/tahir-ali-73319621a) or check out my other projects on [GitHub](https://github.com/tahir-A-ai)!

**Tip**

Want to test your own stocks? Just replace the dataset or modify the ticker column while preprocessing.

**Feedback?**

Questions or improvements? Feel free to reach out or fork the notebook!
