# RFM-Driven-Customer-Segmentation

<h1>Overview</h1>

The "RFM-Driven Customer Segmentation" project utilizes Recency, Frequency, and Monetary (RFM) analysis combined with K-means and hierarchical clustering algorithms to segment customers into distinct groups. This segmentation aids in targeted marketing strategies, improving customer retention, and optimizing resource allocation for customer engagement.

<h1>Introduction</h1>

Understanding customer behavior is crucial for businesses to tailor their marketing efforts effectively. This project employs RFM analysis to quantify customer value and uses clustering algorithms to group customers based on their purchasing behavior. The identified segments provide insights for personalized marketing and engagement strategies.

<h1>Methodology</h1>

<h3>1) RFM Analysis:</h3>

* **Recency**: Time since the last purchase.
* **Frequency**: Total number of purchases.
* **Monetary**: Total amount spent.
  
<h3>2) Clustering:</h3>

* **K-means Clustering**: Identifies distinct groups by minimizing the variance within each cluster.
* **Hierarchical Clustering**: Builds a hierarchy of clusters using a dendrogram.
  
<h3>3)Evaluation:</h3>

* **Silhouette Score**: Evaluates the cohesion and separation of clusters.
* **Elbow Method**: Determines the optimal number of clusters by plotting within-cluster sum of squares.
