# BankWirePayments
This project serves as a valuable resource for anyone looking to understand and analyze bank wire payment transaction data, providing a foundation for more in-depth investigations and the development of predictive models.

📂 Dataset The dataset contains Compliance, status of transaction, AML Score, , credit scores, Amount, transactions fee and time, KYC. Missing values are handled using mean imputation. Features are standardized for clustering analysis.

Visualizing Top Sender and Receiver Banks - Run the visualization_top_banks.py script to generate horizontal bar plots showing the top 10 sender and receiver banks by the total transaction amount.

Visualizing Transaction Status vs. Amount - Run the visualization_status_amount.py script to generate a box plot showing the distribution of transaction amounts for different transaction statuses and a pie chart showing the distribution of transaction statuses.

Visualizing Daily Transaction Volume- Run the visualization_daily_volume.py script to visualize the total transaction amount per day over time using a line plot. Ensure the 'Date' column in the CSV is in a recognizable date format.

Visualizing Transaction Volume by U.S. State- Run the visualization_geographic.py script to create an interactive choropleth map showing the transaction volume by U.S. state. This script assumes a 'Region' column containing U.S. state names.

Data Preprocessing - Run the preprocessing.py script to perform basic data preprocessing steps such as converting the 'Date' column to datetime objects, removing duplicate rows, and handling outliers in the 'Amount' column by capping values at the 99th percentile.

Fraud Analysis - Run the fraud_analysis.py script to explore the relationship between different features and a hypothetical 'FraudCheck' column. This script generates a count plot of 'TransactionAmountCategory' vs. 'FraudCheck', a heatmap of the correlation matrix of numerical features, and a count plot of 'PaymentType' vs. 'FraudCheck'. 

file:///C:/Users/vnjak/Downloads/Map.html
