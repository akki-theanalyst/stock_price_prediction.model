## Table of Content ##
1. Stock Market Price Estimation
2. Project Structure
3. Data Collection
4. Data Description
5. EDA (Exploratory Data Analysis)
     - Comparision of Moving Average
     - Time Series Analysis
     - Removing Outlier
6. Training
    - Models
    - Metrics 
    - Model training.

 ## Stock Market Estimation ##
 Stock Market price estimation is a crucial aspect of financial analysis that impacts investors, companies, and analysis that impacts investors, companies, and analyst alike. The goal is to achieve accurate and reliable results to guide decision-making and minimize risks.

 Inaccurate estimation can lead to:
   - Investor losses: Misleading predictions may cause poor Investment decisions.
   - Market Panic: Overly pessimistic forecasts can trigger unnecssary sell-offs
   - Reputational Risks: Financial institution or analysts may lose credibility.
My aim is to analyze stock market price data for HDFC bank, SBI bank, ICICI bank between May-2022 to May-2025, and provide an estimator while deploying my model both locally and to the cloud.

## Project Structure ##

the project is organized as follows:

stock_price_prediction/
├── eda/
│   ├── eda_stock_market_price_.ipynb
│   └── figures/
├── Inputs/
    hdfc_bank_data.csv
    icici_bank_data.csv
    sbi_bank_data.csv   
├── outputs/
│   ├── icici_scaler.pkl
│   ├── sbi_scale.pkl
│   ├── scaler.pkl
│   ├── stock_price_hdfc_model.keras
│   ├── stock_price_sbi_model.keras
│   ├── stock_price_rnn_icici_model.keras
├── README.md
├── downloading_relevant_data.ipynb
├── main_train_hdfc.py
├── main_train_sbi.py
├── main_train_icici.ipynb
├── requirements.txt





