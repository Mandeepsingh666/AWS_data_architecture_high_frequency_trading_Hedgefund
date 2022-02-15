# AWS_data_architecture_high_frequency_trading_Hedgefund

### Problem 
Spring Capital is an investment bank that owes its success to Big Data analytics. They make
critical decisions about investments based on high-frequency trading data analysis.
High-frequency financial data related to important financial market events, like the price of a
stock, which are collected many times throughout each day.
Spring Capital collects data on trades and quotes from multiple exchanges every day. Their data
the team creates data platforms and pipelines that provide the firm with insights through merging
data points and y calculating key indicators. Spring Capital’s business analysts want to better
understand their raw quote data by referencing specific trade indicators which occur whenever
their quote data is generated, including:
- Latest trade price
- Prior day closing price
- 30-minute moving average trade price (Average price over the past 30 minutes,
constantly updated. This is a common indicator that smooths the price trend and cuts
down the noise.)

### OverView 
In the project, I tried to show my knowledge of AWS's various services. created End-To-End data pipeline where I ingest (Extract) data using AWS lambda from Stock market APIs. 
Then Store raw data into AWS S3 Bucket then I use AWS EMR to transform data to load into AWS Redshift for future Analytical needs. In the end, I use AWS Quicksight for data visualizations. data replication was done to create data fault tolrance and data avalibility in different region.

<img width="640" alt="Screen Shot 2022-02-14 at 7 28 17 PM" src="https://user-images.githubusercontent.com/44817812/153971838-9ccfd281-0388-42cb-98aa-0b8c20b02fda.png">
