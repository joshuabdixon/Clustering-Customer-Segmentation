# Customer Segmentation with Clustering

## Project Overview
This project focuses on applying clustering techniques to perform customer segmentation for an e-commerce company using a dataset provided by SAS. The objective is to identify customer groups based on their purchasing behaviour to inform and enhance marketing strategies.

## Problem Statement
The dataset consists of customer orders from a real-world organisation, covering a range of demographics and purchase behaviours across different continents. The analysis aims to segment customers based on key metrics like frequency, recency, customer lifetime value (CLV), and average unit cost. This segmentation will help the company improve marketing efforts and increase customer satisfaction.

## Techniques and Libraries
- **Clustering Models:** Utilised K-Means and Hierarchical Clustering.
- **Dimensionality Reduction:** Applied PCA and t-SNE for data visualisation.
- **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn` for clustering and data preprocessing.

## Data Overview
The dataset, provided by SAS, contains 951,668 rows, each representing a product ordered by a customer between 1 January 2012 and 30 December 2016. Key features include:
- **Quantity:** Quantity ordered.
- **Location:** City, continent, and country of the customer.
- **Order & Delivery Dates:** Used to calculate recency and delivery times.
- **Total Revenue & Unit Cost:** Used to compute customer lifetime value (CLV).
- **Customer Group & Loyalty Number:** Indicating customer type and loyalty status.

## Methodology
1. **Data Preprocessing:** 
   - Identified and handled missing values and outliers.
   - Performed feature engineering to create key metrics like frequency, recency, CLV, and customer age.
2. **Clustering:** 
   - Utilised K-Means and Hierarchical Clustering to segment customers.
   - Employed the Elbow Method and Silhouette Scores to determine the optimal number of clusters.
3. **Dimensionality Reduction:** 
   - Applied PCA and t-SNE for 2D visualisation of clusters.
4. **Visualisations:** Created boxplots and scatter plots to explore the clusters.

## Key Insights and Achievements
- **Optimal Clustering:** The analysis explored different cluster solutions, with the 2-cluster model achieving a high silhouette score of **0.79**. However, the 3-cluster solution was brought forward in this analysis to provide a more granular segmentation of the customer base. Future analysis will involve a more detailed comparison between the 2-cluster and 3-cluster models to determine which aligns best with the business context.
- **PCA for Dimensionality Reduction:** Applied PCA to reduce the dataset to two principal components, capturing **100% of the variance** and facilitating the effective visualisation of the clusters.
- **Actionable Insights:** Identified distinct customer segments based on purchasing behaviours, including variations in frequency, recency, CLV, and spending patterns.
- **Recommendations:** Provided tailored marketing strategies for each identified cluster, including loyalty programs, re-engagement initiatives, and promotional campaigns aimed at maximising customer value.

## Files in This Repository
- **Customer Segmentation with Clustering.ipynb:** The Jupyter Notebook containing the full analysis, including data preprocessing, clustering, and visualisation.
- **Customer Segmentation with Clustering - Summary Report.pdf:** A concise report summarising the methodology, key insights, and recommendations for marketing strategies.
- **LICENSE:** The license file for the project.
- *Note:* The raw data is not included to ensure compliance with data privacy standards.

## Usage
Open the `Customer Segmentation with Clustering.ipynb` notebook to explore the full analysis, including data processing, clustering, and customer segmentation insights. Refer to the summary report for an overview of the findings and recommendations.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
