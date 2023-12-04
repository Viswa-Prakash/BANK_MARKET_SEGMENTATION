# BANK_MARKET_SEGMENTATION

Marketing is crucial for the growth and sustainability of any business. Marketers can help build the company's brand, engage customers, grow revenue and increase sales.
- Growth: Marketers empowers business growth by reaching new customers.
- Education: Marketers educates and communicate value proposition to customers.
- Drive Sales: Marketers drive sales and traffic to products/services.
- Engagement: Marketers engage customers and understand their needs.
In this case study, the bank has extensive data on their customers for the past six months. The marketing team at the bank wants to launch a targeted ad marketing campaign by dividing their customers into at least 3 distinctive groups.

The dataset contains the following informations:
- CUSTID: Identification of Credit Card holder 
- BALANCE: Balance amount left in customer's account to make purchases
- BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- PURCHASES: Amount of purchases made from account
- ONEOFFPURCHASES: Maximum purchase amount done in one-go
- INSTALLMENTS_PURCHASES: Amount of purchase done in installment
- CASH_ADVANCE: Cash in advance given by the user
- PURCHASES_FREQUENCY: How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
- ONEOFF_PURCHASES_FREQUENCY: How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
- PURCHASES_INSTALLMENTS_FREQUENCY: How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
- CASH_ADVANCE_FREQUENCY: How frequently the cash in advance being paid
- CASH_ADVANCE_TRX: Number of Transactions made with "Cash in Advance"
- PURCHASES_TRX: Number of purchase transactions made
- CREDIT_LIMIT: Limit of Credit Card for user
- PAYMENTS: Amount of Payment done by user
- MINIMUM_PAYMENTS: Minimum amount of payments made by user
- PRC_FULL_PAYMENT: Percent of full payment paid by user
- TENURE: Tenure of credit card service for user

Determined the optimal number of clusters using the elbow method. Applied KMeans clustering with the chosen number of clusters (8 in this case). Analyzed the characteristics of each cluster based on cluster centers.

Applied PCA to reduce the dimensionality to 2 components. Visualized the data points in 2D space with different colors representing clusters.

Implemented an autoencoder neural network for dimensionality reduction. Trained the autoencoder on the scaled data. Used the encoder part of the trained autoencoder to obtain encoded representations. Applied KMeans clustering on the encoded representations. Visualized the results using PCA on the encoded representations.

Plotted histograms for each feature within different clusters for both KMeans and autoencoder-based clustering. Visualized the clusters in 2D space after dimensionality reduction.
