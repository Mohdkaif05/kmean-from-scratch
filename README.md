In this project I analyse the dataset of Online Retail provided by UC Irvine Machine Learning Repository.
Information about dataset available of site :
InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation. 
StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product. 
Description: Product (item) name. Nominal. 
Quantity: The quantities of each product (item) per transaction. Numeric.	
InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated. 
UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£). 
CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer. 
Country: Country name. Nominal. The name of the country where a customer resides.

I have followed this roadmap for analysis : EDA -> Data Cleaning -> Feature Engineering -> Modal Training (using Kmean Clustering) -> finding out pattern by framing graphs.

Result of Analysis :
Cluster 0 :
High-value customers who purchase regularly, though not recently.Focus is on retention to maintain loyalty and spending.
Cluster 1 :
Lower-value, infrequent buyers who haven’t purchased recently.Goal is to re-engage and revive purchasing behavior.
Cluster 2:
Least active and lowest-value customers, but they’ve made recent purchases. May be new customers.
Cluster 3:
High-value, very frequent buyers who are still actively purchasing.These are your most loyal customers.
