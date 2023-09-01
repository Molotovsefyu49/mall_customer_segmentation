# Mall Customer Segmentation using K-Means Clustering

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Customer segmentation is a crucial aspect of marketing strategy. By dividing customers into distinct groups based on their behavior, preferences, or characteristics, businesses can tailor their approaches to better meet customer needs. This project focuses on using K-Means clustering, a popular unsupervised machine learning technique, to segment customers of a mall based on their annual income and spending score.

## Project Overview
In this project, we apply the K-Means clustering algorithm to segment mall customers. The dataset consists of customers' annual income and spending score. The main steps of the project are as follows:

1. **Importing Libraries and Data:** We start by importing necessary libraries for data manipulation and visualization. We load the dataset containing customer information.

2. **Finding Optimal Number of Clusters:** We use the elbow method to determine the optimal number of clusters for K-Means. This involves calculating the Within-Cluster Sum of Squares (WCSS) for different cluster counts and plotting the WCSS values against the number of clusters.

3. **Training K-Means Model and Creating Clusters:** Based on the elbow method, we choose an appropriate number of clusters and train the K-Means model on the dataset. The algorithm assigns each data point to a cluster.

4. **Visualizing Clusters:** We visualize the clusters by creating a scatter plot. Each cluster is assigned a distinct color, and the cluster centroids are marked with yellow.

## Getting Started
To run the project on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/Molotovsefyu49/mall_customer_segmentation.git`
2. Navigate to the project directory: `cd mall-customer-segmentation`
3. Make sure you have the necessary dependencies (see the next section).
4. Run the project script: `python mall_segmentation.py`

## Dependencies
Ensure you have the following dependencies installed:

- Python (>= 3.6)
- NumPy
- Pandas
- Matplotlib
- scikit-learn

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Usage
Modify the dataset file path in the script to point to your own dataset if needed:

```python
dataset = pd.read_csv('path/to/your/Mall_Customers.csv')
```

Run the script to perform the customer segmentation and visualize the results.

## Results
The project results in a visualization that shows how customers are segmented into distinct clusters based on their annual income and spending score. Each cluster is assigned a unique color, and the cluster centroids are marked with yellow. This visualization helps understand customer groups and can guide marketing strategies.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
