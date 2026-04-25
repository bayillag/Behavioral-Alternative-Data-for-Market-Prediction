# Behavioral-Alternative-Data-for-Market-Prediction
## Project Overview
This project investigates the operationalization of behavioral alternative data to enhance market trend prediction for the **SPY ETF**. Utilizing a longitudinal archive of **3.27 million StockTwits messages**, we implement a high-frequency sentiment index synchronized with NYSE trading hours. 

The methodology integrates optimized technical indicators with a Multilayer Perceptron (MLP) neural network, following the parsimonious design principles required to mitigate the "curse of dimensionality" in financial machine learning.

## Dataset
The data used in this study is hosted on Kaggle:  
[StockTwits Sentiment Data: Behavioral Alternative Data for Market Prediction](https://www.kaggle.com/datasets/bayillageda/stocktwits-sentiment-data)

## Key Findings
* **Temporal Alignment:** Intraday sentiment peaks during the first two hours of the NYSE session, serving as a leading indicator for price discovery.
* **Information Asymmetry:** Nontraditional behavioral signals provide a quantitative window into "Crowd Anxiety" not captured by lagging fundamental data.
* **Optimization:** Reducing network topology to salient features resulted in an 84.68% reduction in training time with a net gain in accuracy.

## Core Bibliography
* **Goldstein, I., Spatt, C. S., & Ye, M. (2021).** Big Data in Finance. *The Review of Financial Studies*.
* **Renault, T. (2017).** Intraday Sentiment and Stock Returns. *Journal of Banking & Finance*.
* **López de Prado, M. (2018).** *Advances in Financial Machine Learning*. John Wiley & Sons.
* **Sezer, O. B., et al. (2020).** Financial Time Series Forecasting with Deep Learning. *Applied Soft Computing*.

## License
Distributed under the MIT License. See `LICENSE` for more information.
