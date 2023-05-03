# Mall-Customers-Dataset-Clustering
This project implements K-means clustering on the Mall Customers dataset, a popular dataset for customer segmentation and clustering. The project is implemented using Google Colab, a free Jupyter notebook environment that allows you to run Python code in the cloud.

## Dataset
The Mall Customers dataset contains information about customers' demographic and spending characteristics. It consists of 200 rows and 5 columns:

### CustomerID: 
unique ID assigned to each customer
### Gender: 
gender of the customer (male or female)
### Age: 
age of the customer
### Annual Income (k$): 
annual income of the customer in thousands of dollars
### Spending Score (1-100): 
score assigned by the mall based on customer behavior and spending nature
## Methodology
The K-means clustering algorithm is used to cluster the customers based on their annual income and spending score. The optimal number of clusters is determined using the elbow method, and the Silhouette score is used to evaluate the quality of the clustering. The following steps are followed:

Load the Mall Customers dataset.
Select the features to be used for clustering.
Determine the optimal number of clusters using the elbow method.
Fit the K-means model with the optimal number of clusters.
Obtain the predicted cluster labels for each customer.
Calculate the Silhouette score to evaluate the quality of the clustering.
## Requirements
This project requires the following libraries:

pandas
numpy
matplotlib
scikit-learn
These libraries are pre-installed in Google Colab, so you don't need to install them manually.

## Usage
To use this project, follow these steps:

Open the mall_customers_clustering.ipynb notebook in Google Colab.
Click on the "Runtime" menu and select "Run all".
This will load the dataset, perform K-means clustering, and display the Elbow plot and Silhouette score.
Results
The Elbow plot suggests that the optimal number of clusters is 5. After fitting the K-means model with 5 clusters, the Silhouette score is calculated to be 0.553, which indicates a reasonable clustering quality.

## Future Work
Possible future work includes trying different clustering algorithms, such as hierarchical clustering or DBSCAN, and comparing their performance to K-means clustering. It may also be interesting to include other features in the clustering analysis, such as age or gender, and to perform a more detailed analysis of the clusters, such as identifying the characteristics of each cluster and their potential marketing implications.





