# Crypto Arbitrage Analysis

This repository contains a collection of Jupyter notebooks and Python scripts designed to analyze arbitrage opportunities in cryptocurrency markets across different exchanges for the SOL/USDT pair. 

## Notebooks

- `arbitrage.ipynb`: This notebook calculates the arbitrage index and the potential profit from arbitrage opportunities.

- `correlations.ipynb`: This notebook explores the cross-correlation of cryptocurrency prices among various exchanges. It employs the Hayashi-Yoshida correlation estimator to assess the lead-lag relationships between different trading platforms.

## Data Preprocessing

- `data_export.ipynb`: A preprocessing script that prepares raw data files by converting them to the appropriate format. It also merges multiple data files from the same exchange into a single file for further analysis.

- `data_processing.ipynb`: Performs data cleaning and exploratory data analysis. It computes statistics for prices, trading volumes, and returns.

## Scraping Scripts

- `kucoin_scrapping.ipynb`: A scraping tool that extracts data from the KuCoin exchange's website.

- `okx_scrapping.ipynb`: Similar to the KuCoin scraper, this script is tailored for scraping data from the OKX exchange website.

## Arbitrage Calculation

- `triangular_arbitrage.ipynb`: This notebook calculates opportunities for triangular arbitrage within the cryptocurrency markets, focusing on Bitcoin and Solana across various exchanges.

## Getting Started

To use these notebooks, clone the repository and install the required dependencies listed in `requirements.txt`.

```bash
git clone https://github.com/your-username/crypto_arbitrage.git
cd crypto_arbitrage
pip install -r requirements.txt
