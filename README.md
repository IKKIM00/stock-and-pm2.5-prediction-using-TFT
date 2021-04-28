# General Description 
Applied to new dataset using Google's TFT

paper link: https://arxiv.org/pdf/1912.09363.pdf

This is an implemetation of stock dataset and pm2.5 dataset to predict future value.

For stock dataset, used 50 days of historical data to predict the next day's 'Close' value.

For beijing pm2.5 dataset, used 24 hours of historical data to predict the next hour's 'pm 2.5 concentration'

# Download Dataset
You can download each dataset through below url.

### stock dataset
https://finance.yahoo.com/quote/CSV?p=CSV&.tsrc=fin-srch 

Also uploaded data used as `stock.csv`

### beijing pm2.5 dataset
https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data

# How to use

## TFT
1. git clone https://github.com/google-research/google-research.git
2. For beijing pm2.5 dataset, run all cells in `pm2.5_tft.ipynb`
3. For stock dataset, run all cells in `carriage_service_tft.ipynb`

## Single LSTM
1. For beijing pm2.5 dataset, run all cells in `singleLSTM_beijing_pm_2.5`
2. For stock dataset, run all cells in `singleLSTM_carriage_service`

## Stacked LSTM
1. For beijing pm2.5 dataset, run all cells in `stackedLSTM_beijing_pm_2.5`
2. For stock dataset, run all cells in `stackedLSTM_carriage_service`
