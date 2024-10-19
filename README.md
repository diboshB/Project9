# Project9
Fraud Detection - Power BI

Dataset Overview:
The dataset contains information on various financial transactions, including payments, transfers,
and cash-outs. Each transaction includes details such as the type of transaction, the origin and
destination accounts, and whether the transaction was fraud or not.
Tasks:
• Visualize Transaction Types and Volumes:
Create a visualization that shows the distribution of different transaction types (PAYMENT,
TRANSFER, CASH_OUT, etc.).
Highlight the total transaction volume and amount per transaction type.
• Identify Fraudulent Transactions:
Visualize the percentage of fraudulent transactions compared to non-fraudulent ones.
Create a chart showing the number of fraud and non-fraud transactions.
Check and visualize any pattern w.r.t. type, time, amount etc.
Conclusions and Insights:
Based on your visualizations, identify key insights and potential red flags that could help in detecting
fraud.
Suggest improvements or recommendations for fraud detection based on your analysis.
• Deliverables:
A Power BI dashboard with all the required visualizations.
A brief report summarizing your findings and explaining the insights gained from the dashboard.
Data Dictionary:
• step - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744
(30 days simulation).
• type - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
• amount - amount of the transaction in local currency.
• nameOrig - customer who started the transaction
• oldbalanceOrg - initial balance before the transaction
• newbalanceOrig - new balance after the transaction
• nameDest - customer who is the recipient of the transaction
• oldbalanceDest - initial balance recipient before the transaction.
• newbalanceDest - new balance recipient after the transaction.
• isFraud - This is the transactions made by the fraudulent agents inside the simulation. In this
specific dataset the fraudulent behavior of the agents aims to profit by taking control or
customers’ accounts and try to empty the funds by transferring to another account and then
cashing out of the system.
(This is the label for fraud transactions)
• isFlaggedFraud - The business model aims to control massive transfers from one account to
another and flags illegal attempts. An illegal attempt in this dataset is an attempt to transfer more
than 200.000 in a single transaction.
