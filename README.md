# LAB-11
1. Why is this an unsupervised learning problem?
This is an unsupervised learning problem because the dataset does not contain labeled outputs or predefined customer groups. The algorithm discovers patterns and clusters automatically.

2. Why did we remove the CUST_ID column?
We removed the CUST_ID column because it is only a customer identifier and does not provide useful information for clustering.

3. Which columns had missing values?
The columns with missing values were:
- MINIMUM_PAYMENTS
- CREDIT_LIMIT

4. How did you handle the missing values?
The missing values were replaced using the mean value of each column.

5. Why is scaling important before applying K-Means?
Scaling is important because K-Means uses distance calculations. Features with larger numerical values can dominate the clustering process if the data is not scaled.

6. Which K value did you choose? Explain your answer using the elbow method and silhouette score.
We chose K = 4 because the elbow method showed a noticeable bend around 4 clusters, and the silhouette score was relatively high at this value. This indicates good cluster separation and grouping.

7. Based on the cluster summary table, describe each customer segment in your own words.

Cluster 0:
Customers with low balances and low spending activity. These customers use their credit cards less frequently.

Cluster 1:
Customers with high purchase activity and frequent transactions. These are active card users.

Cluster 2:
Customers with high cash advance usage and larger balances. These customers rely more on credit and cash advances.

Cluster 3:
Customers with high credit limits and regular payments. These customers are financially stable and valuable to the company.

8. Which cluster may represent high-value customers?
The cluster with high purchases, high credit limits, and consistent payments may represent high-value customers because they actively use their credit cards responsibly.

9. Which cluster may represent customers who rely more on cash advance?
The cluster with the highest CASH_ADVANCE values likely represents customers who rely more on cash advances.

10. How can a company use these clusters for marketing strategy?
A company can use these customer segments to create targeted marketing campaigns, provide personalized offers, improve customer satisfaction, and develop better financial products for each customer group.
