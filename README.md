# Customer-Segmentation-for-the-Telecommunications-Sector
An unsupervised clustering project using Dataiku to segment telecommunications customers, enabling tailored marketing strategies and improving customer retention.

# Customer Segmentation for the Telecommunications Sector

This project utilizes clustering techniques to segment customers in the telecommunications sector. By identifying distinct groups based on payment preferences and service usage, the project provides actionable insights for targeted marketing strategies and retention efforts.

## Project Overview

Customer segmentation is crucial for understanding diverse preferences and behaviors. Using the K-Means clustering algorithm in Dataiku, this project segments customers into four distinct groups, enabling the design of tailored promotional campaigns and enhancing service retention strategies.

### Key Features:
- **Cluster Identification:** Segments customers into four groups based on payment preferences, service usage, and churn likelihood.
- **Actionable Insights:** Provides specific recommendations for loyalty and retention strategies tailored to each group.
- **Behavioral Analysis:** Focuses on call usage patterns, payment methods, and service preferences to identify unique customer profiles.

## Methodology

1. **Data Preparation:**
   - Conducted initial variable analysis, adjusting dummy variables to mitigate influence imbalances.
   - Removed irrelevant variables (e.g., gender, age) based on correlation and clustering relevance.

2. **Clustering Approach:**
   - Applied K-Means clustering with multiple configurations (k = 3 to 7).
   - Selected the optimal model with k = 3 clusters and a distinct outlier group, achieving a silhouette score of 0.46.

3. **Cluster Profiling:**
   - Profiled groups based on payment preferences (credit card, cash, bank account) and call patterns (local, long-distance, international).
   - Identified churn risks within each cluster.

## Results and Insights

### Customer Segments:

| **Segment**  | **Profile**                                                                                  | **Key Characteristics**                                                                                           |
|--------------|----------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| **Group A**  | Credit Card Payers                                                                           | High credit card usage, preference for local and national long-distance calls.                                   |
| **Group B**  | Cash Payers                                                                                  | High cash usage, interested in international discounts but with low international call usage.                    |
| **Group C**  | Bank Account Payers                                                                          | No predefined service preference, moderate call usage.                                                           |
| **Group D**  | Long Calls Customers                                                                         | High international and local call usage, profitable but high churn risk.                                         |


### Key Metrics:
- **Group A:** Represents 53.79% of customers; average churn rate 44%.
- **Group D:** Smallest group (9.21%) but highly profitable with the highest churn rate (57%).

## Recommendations

### Loyalty Strategies:
- **Group A:** Introduce credit card-linked benefits, such as discounts on local or national long-distance calls.
- **Group B:** Design promotions for cash payments, linking local call usage to international call discounts.
- **Group C:** Develop personalized offers based on individual usage patterns to boost service engagement.

### Retention Strategies:
- **Group D:** Implement tailored campaigns focusing on long international and local calls with loyalty incentives to mitigate churn.

