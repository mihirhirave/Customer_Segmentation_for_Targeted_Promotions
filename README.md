# Customer Segmentation for Targeted Promotions

## Overview
This project focuses on customer segmentation for a bank using various clustering techniques. The goal is to identify distinct customer groups and provide strategic insights for targeted marketing and product offerings.

## Dataset
The dataset includes customer information such as:
- Demographic data (age, income, marital status, number of children)
- Financial product usage (checking account, savings account, personal equity plan, mortgage)
- Geographic location (encoded as inner city, town, rural, suburban)

## Analysis Steps

1. **Data Preprocessing**
   - One-hot encoding of categorical variables (region)
   - Logarithmic transformation of skewed variables (income)

2. **Hierarchical Clustering**
   - Applied five linkage methods: centroid, single, complete, average, and Ward
   - Evaluated clusters using dendrogram visualization

3. **K-means Clustering**
   - Applied for k values of 3, 4, 5, 6, 7, and 8
   - Compared results with hierarchical clustering

4. **Cluster Analysis**
   - Identified distinguishing characteristics of each cluster
   - Compared results between hierarchical and k-means clustering

## Key Findings

- Ward linkage method provided the best results in hierarchical clustering
- K-means clustering with k=5 offered more detailed and actionable insights
- Identified distinct customer segments based on age, income, and financial product usage
- Developed strategic recommendations for targeting specific customer groups

## Tools and Libraries Used

- Python
- Pandas (for data manipulation)
- Scikit-learn (for clustering algorithms)
- Matplotlib (for visualizations)

## Strategic Insights

- Tailored marketing strategies for different age groups and life stages
- Identified opportunities for promoting specific financial products (e.g., PEP, mortgages) to relevant customer segments
- Suggested financial counseling services for young families

## Future Work

- Incorporate additional customer data for more refined segmentation
- Explore other clustering techniques or ensemble methods
- Conduct time-series analysis to understand changing customer behaviors
