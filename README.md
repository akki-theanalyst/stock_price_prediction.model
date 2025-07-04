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

```Stock_price_prediction/
├── input/             # Raw CSV data files
├── EDA/               # EDA notebooks, scripts, and saved PNG graphs
├── output/            # Trained model files (.pkl, .keras)
├── scripts/           # Python scripts for data download and model training
├── requirements.txt   # Project dependencies
├── main.py            # Entry point if needed
└── README.md          # Project documentation




