📈 Power BI Stock Broker Customer Visualization & Analytics

This repository features a comprehensive Stock Broker Customer Visualization system. The core of this project is a robust financial data engine I developed to simulate a real-world brokerage environment, tracking assets, transactions, and customer health through advanced BI. 

🏗️ Project Architecture

The project follows a structured data pipeline, ensuring that every visual insight is backed by logical financial data engineering.
Data Generation (Python): Custom scripts created to maintain relational integrity across customers, trades, and holdings. 
Relational Storage: Structured data stored in optimized CSV files for high-performance BI modeling. 
BI Layer (Power BI): An interactive multi-page dashboard designed for Executive and Branch-level decision-making. 

🛠️ Innovative Data Engineering

Unlike a standard static dataset, this project includes a dynamic engine that reflects the complexities of the financial sector:
Relational Synchronization: Every portfolio_value in the holdings table is logically consistent with the historical Buy/Sell transactions for that customer. 
Automated Brokerage Logic: Simulated revenue model by calculating a 0.5% brokerage fee for Equity transactions, allowing for profitability analysis. 
RFM Scoring Engine: An innovative segmentation model that scores clients on Recency, Frequency, and Monetary value to drive targeted marketing. 
Spatial Wealth Analysis: AUM mapping across major South Indian hubs including Thiruvananthapuram, Kochi, Coimbatore, and Bengaluru. 

📊 Business Intelligence Dashboard

The Power BI suite provides a 360-degree view of the brokerage’s health:
1. Executive Portfolio Overview
   Total AUM: Currently managing 1.33 Billion in assets.
   Regional Dominance: Thiruvananthapuram leads with 35.94% of total AUM, followed by Kochi at 33.87%.
   Product Performance: Detailed tracking across Mutual Funds ($31.8M$) and Equity ($29.4M$).
2. Customer Health & Priority MatrixThe dashboard features a "Top Priorities" matrix to help branch managers focus on high-impact clients:

📁 Repository Structure

Customer.csv: Investor demographics and geographic data. 
Transactions.csv: Historical trade logs with calculated brokerage. 
Holdings.csv: Real-time portfolio snapshots across asset classes. 
Products.csv: Product category master list (Equity, MF, PMS). 
powerbi.pdf: The full multi-page visual report export. 
powerbi.pbix: Visualization in powerBI format

🚀 Future Roadmap

[ ] Integrate Predictive Churn Analysis based on transaction frequency.
[ ] Add Portfolio Variance and Sharpe Ratio calculations for risk management.
[ ] Implement a live API connection for real-time stock price updates.
