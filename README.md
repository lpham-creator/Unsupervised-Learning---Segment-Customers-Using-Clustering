# Unsupervised Learning - Segment Customers Using Clustering

## Introduction

Customer segmentation is the process of dividing customers into groups based on common characteristics such as demographics, interests, and behavior. The goal is to identify key customer segments to allow for more targeted marketing and product development.

This project performs customer segmentation on mall customer data to identify the key shopping groups based on income, age, and mall shopping score.

## Business Problem

The marketing team wants to identify the most important customer segments to better target marketing activities. The boss has requested an ideal number of segments labeled with a name for each one.

## Technology Used
- **Language**: Python

- **Libraries**:
  - Pandas
  - Seaborn
  - Matplotlib.pyplot
  - Numpy
  - Sklearn.cluster KMeans

## Approach

The following approach was taken:

- **Exploratory Data Analysis**
  - Loaded the data and checked for null values
  - Plotted histograms of the features to understand distributions
  - Calculated summary statistics on the data

- **Preprocessing**
  - Scaled the features for use in K-Means clustering
  - Determined the optimal number of clusters using the elbow method

- **Modeling**
  - Applied K-Means clustering to segment customers
  - Calculated summary statistics on the clusters

- **Evaluation**
  - Compared cluster assignments to original data
  - Validated clustering performance

## Key Learning

- Understanding the importance of choosing the optimal number of clusters for effective segmentation.
- Implementing preprocessing techniques such as feature scaling to ensure accurate clustering results.
- Utilizing the elbow method to determine the appropriate number of clusters for the K-Means algorithm.
- Assigning meaningful cluster names based on key differentiators for effective interpretation and communication of results.

## Key Struggles

- Managing outliers and their potential impact on clustering accuracy.
- Balancing computational resources with the need for comprehensive data exploration and analysis.
- Interpreting complex data distributions and identifying appropriate preprocessing techniques for accurate insights.
- Addressing potential data inconsistencies and their implications on the final segmentation outcomes.

## Key Insights

- 5 clusters provided the ideal segmentation based on the elbow plot
- The clusters showed clear separation based on income and shopping score
- Cluster names were assigned based on distinguishing characteristics
- Visualizations provided additional validation of cluster uniqueness

## Conclusion

This analysis successfully identified 3 key customer segments for the mall using K-Means clustering. These groups can be targeted with tailored marketing strategies based on a deeper understanding of their demographics and shopping behavior. The project demonstrated how unsupervised learning can be leveraged for customer segmentation.

## Future Work

- Incorporate additional features like purchase history
- Apply hierarchical clustering methods
- Implement new customer data to identify updated segments