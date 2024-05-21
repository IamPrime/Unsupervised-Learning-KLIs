# Unsupervised-Learning-KLIs
Segmentation analysis of members data using customer to account table, monthly balance data, and Key Lifestyle Indicator

## Conclusions
The KLI and monthly transaction data for both Savings and Checkings customers did not produce any meaningful customer segments. Therefore, the savings and checkings accounts were considered seperately.

Segmenting Savings Account customers into three distinct groups was achieved by categorizing the 'Key Lifestyle Indicators' (KLIs) variable into 11 factor levels. The top 10 most frequent KLIs in the dataset were identified, while all other indicators were grouped into a category labeled 'Other.' Utilizing this refined categorical variable, as well as the Monthly Balance data, we identified 3 customer segments. These customer segments are delineated by the frequency of transactions on an account, the membership period, and the monthly account balances maintained. The following variables contribute to each of the 3 customer segments.

Cluster 1: The variables that contribute to the first segment include: Primary account holders, Employed, Competitive Bill Pay, Home Improvement Store Patron, Deep Discount or Dollar Store, Ice Cream Lover, Delivery and Takeout Restaurant Customers, as well as the difference between their maximum and minimum account balance.

Cluster 2: The customer that are not primary account holders, have Other KLI, the difference in their monthly account balance and their period of membership with the bank contribute to this cluster.

Cluster 3: The Customers that are primary account holders, and their average balance, number of transaction and those that have 'Other' as their Key Lifestyle Indicator.

These segments show unique characteristics and diverse needs of Savings Account holders that can be harnessed to achieve personalised customer experience.

The Checkings Customers, their KLIs and monthly transactions resulted in 2-3 overlapping segments. Their features were similar across the different segments and could not be distinguished clustered.

From the monthly balance data, the averagebalance, transaction frequency, membership period, and the balance maintained each month, the customers were segmented into 3 distinct groups. The data was reduced into 3 Principal components using PCA. The final segmentation was based on 2 Principal components since they explained about 62% of the variance in the data. The number of transactions, period of membership and average monthly balance contributed to segmenting the customers into these 3 groups.

## Some key takeaways: ## Using a high value for the nstart argument while running the kmeans() clustering provided better results since the kmeans clustering was performed with multiple random assignments. It results in a desirable local optimum. Additionally, using the within-cluster sum of squares showed that the data was complex and clusters selection was subjective. Further, reducing the data to about 200,000 observations improved the performance of the server.
