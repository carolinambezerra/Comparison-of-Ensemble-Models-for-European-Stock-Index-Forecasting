# Comparison-of-Ensemble-Models-for-European-Stock-Index-Forecasting

## Summary

### Objectives
- Improve forecasting accuracy by leveraging advanced deep learning and ensemble techniques.
- Compare the performance of various ensemble and hybrid models.
- Assess the impact of economic indicators on predictive accuracy.

### Dataset
The dataset includes daily data from 2010 to 2020 for:
- Stock market indices: EURO STOXX 50, FTSE 100, DAX, CAC 40, AEX, IBEX 35, SMI, PSI 20.
- Economic indicators: Exchange rates (EURUSD, GBPUSD, EURGBP), commodity prices (Crude Oil, Gold).

### Methodology
- **Base Models**: LSTM, GRU, BiLSTM, CNN, Transformer, KAN, Autoencoder, ANN.
- **Ensemble Strategies**: Averaging, Stacking, Bagging, Boosting, Voting.
- **Data Preprocessing**: Handling missing values, feature engineering, normalization, feature selection.
- **Time-Series Analysis**: Log returns, moving averages, stationarity testing, decomposition.

### Results
Detailed results are provided in the thesis.

## Requirements
- Python 3.10.12
- TensorFlow 2.15.0
- Keras 2.15.0
- NumPy 1.25.2
- Pandas 2.0.3
- Statsmodels 0.14.2
- Scikit-learn 1.2.2
- Matplotlib 3.7.1
- Seaborn 0.13.1
- SciPy 1.11.4
- XGBoost 2.0.3
- PyTorch 2.3.0+cu121
- yFinance
