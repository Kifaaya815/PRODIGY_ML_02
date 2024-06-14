# Customer Segmentation Using K-Means Clustering

This project demonstrates the use of the K-Means clustering algorithm to group customers of a retail store based on their purchase history. The dataset used contains information about the customers' annual income and spending score.

## Project Overview

Customer segmentation is a crucial aspect of marketing that allows businesses to tailor their strategies to different groups of customers. By understanding customer segments, businesses can better meet the needs of their customers, improve customer satisfaction, and increase revenue.

In this project, we apply the K-Means clustering algorithm to a dataset of mall customers. The goal is to segment the customers into distinct groups based on their annual income and spending score.

## Dataset

The dataset used in this project is `Mall_Customers.csv`, which contains the following columns:
- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousand dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Project Steps

1. **Load and Inspect the Data**: Load the dataset and perform initial data inspection to understand its structure and check for missing values.
2. **Feature Selection**: Select relevant features for clustering. In this case, we use `Annual Income (k$)` and `Spending Score (1-100)`.
3. **Determine Optimal Number of Clusters**: Use the Elbow method to find the optimal number of clusters by plotting the within-cluster sum of squares (WCSS) against the number of clusters.
4. **Apply K-Means Clustering**: Fit the K-Means algorithm to the data using the optimal number of clusters.
5. **Visualization**: Visualize the resulting clusters and their centroids.

## Dependencies

The project requires the following Python libraries:
- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `matplotlib`: For data visualization
- `sklearn`: For the K-Means clustering algorithm

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
