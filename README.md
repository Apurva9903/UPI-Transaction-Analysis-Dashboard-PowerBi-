# UPI-Transaction-Analysis-Dashboard-PowerBi-

## 📊 Project Overview
This project transforms the UPI+Transactions.xlsx dataset into an interactive decision-support tool. By leveraging Power BI, the dashboard visualizes the flow of digital capital, identifies preferred merchants (e.g., Amazon, Zomato, Swiggy), and maps out the purpose of transactions—ranging from food and travel to bill payments. 

## 🛠️ Data ArchitectureData Source:
UPI+Transactions.xlsx, featuring 20 unique data points per transaction.  ETL Layer: Data cleaning and standardization performed in Power Query to handle diverse currencies and transaction modes.  Modeling: A star-schema approach to connect customer accounts, merchant accounts, and temporal data.  Measures: Custom DAX for calculating remaining balances, success rates, and volume-over-time.  

## 📈 Key Visualizations & MetricsGeographic Distribution: 
Visualizing transaction volume across major cities like Delhi, Bangalore, and Hyderabad.  Merchant Leaderboard: Identifying top-performing merchants such as Amazon, Flipkart, and IRCTC.  Channel Preference: Comparative analysis of PaymentModes (Instant vs. Scheduled) and PaymentMethods (QR vs. UPI ID).  Demographic Segmentation: Transaction patterns segmented by Gender and Age. 

## 🚀 How to RunClone the repository.
Open the .pbix file in Power BI Desktop.Connect the data source to the provided UPI+Transactions.xlsx.



## Dashboard:
<img width="2110" height="1200" alt="image" src="https://github.com/user-attachments/assets/8e9a04a5-7c36-4d20-bdaa-d5e336d6407c" />
