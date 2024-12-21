# Stock Portfolio Forecasting and Optimization on S&P500

Made by: 

- [Filipe Barros](https://github.com/filipeazuil)
- [Joao Barao](https://github.com/jbarao04)
- [Goncalo Arrobas](https://github.com/Garrobas)



### Project Overview
The stock market is highly volatile, making it challenging to predict returns and optimize portfolios. This project aimed to leverage machine learning techniques to forecast daily returns of S&P 500 stocks and apply optimization methods to maximize cumulative returns. 

To streamline the process, we started with the SPY ETF, which mirrors the S&P 500. This allowed us to efficiently test and refine our models.

### Data
The dataset consists of CT scan images from 1,010 patients. Each scan image includes detailed visual information that enables us to identify patterns associated with malignancy. Using feature extraction methods, we transform these images into a structured dataset, allowing for efficient analysis and model training.

# Project Roadmap
### 1. Feature Engineering
Notebook: FeatureEngineering - SPYForecasting.ipynb

Description: Our approach involved creating a comprehensive set of features, including:

- Daily Trading Data (e.g., closing price, volume),
- Seasonality (Day of the week, month)
- Technical Indicators (like moving averages, MACD, Bollinger Bands),
- Macroeconomic Variables (interest rates, unemployment),
- Market Conditions inspired by Wyckoff’s methodology.

### 2. Model Implementation 
Notebook: SPYForecasting.ipynb and StockMarketPrediction.ipynb

Description: We implemented Deep Learning models such as LSTMs and Machine Learning models such as Random Forests and SVMs.

### 3. Clustering
Notebook: Dataengineering.ipynb

Description: This notebook includes the implementation of machine learning models, including SVM, Random Forest, and an ensemble model. Hyperparameter tuning with Grid Search and model evaluation are also performed here, prioritizing sensitivity for accurate detection of malignant cases.

### 4. Portfolio Optimization
Notebook: LungCancerClassification.ipynb

Description: The final results are analyzed and visualized, with a focus on metrics like AUC, sensitivity, and specificity. This step highlights the model’s effectiveness in distinguishing between benign and malignant nodules.

# Requirements

To install the requirements, run:

```bash
pip install -r requirements.txt
```

# References

