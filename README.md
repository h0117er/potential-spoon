# potential-spoon

## 📊 Project Overview

This project explores Ethereum-based stablecoin(ERC-20) transactions using Google BigQuery public datasets.  
The analysis aims to identify transaction patterns, user activity trends, and the relationship between on-chain movements and market events.

## 💡 Motivation 

Stablecoins are vital for maintaining liquidity in the crypto ecosystem.  
However, there is a lack of systematic analysis of their actual on-chain movement in the existing studies.  
This project will bridge that gap through data-driven insights.

## 🗄️ Data Source

- **Google BigQuery public datasets**  
  - `bigquery-public-data.crypto_ethereum.transactions`  
  - `bigquery-public-data.crypto_ethereum.token_transfers`
- Time range: Jan 2023 – Oct 2025
- Tokens analyzed: USDT, USDC, DAI

## 🧰 Tools & Libraries

- **Python**: pandas, matplotlib, seaborn, plotly, google-cloud-bigquery  
- **Environment**: Jupyter Notebook, Google Cloud SDK  
- **Optional Tools**: ydata-profiling (EDA automation), looker studio (dashboard)

## ⚙️ Analysis Workflow 

1. Connect to BigQuery and query on-chain transaction data  
2. Clean and aggregate data by token and time window  
3. Visualize transfer volume trends and user activity  
4. Interpret market-related implications
