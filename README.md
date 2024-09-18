# Mall Customer Segmentation

#Project Overview

Mall Customer Segmentation is the process of grouping customers based on their demographic characteristics and purchasing behavior. By leveraging clustering techniques, businesses can identify distinct customer profiles, enabling more personalized marketing, improved customer satisfaction, and increased sales.

This notebook analyzes the Mall Customer Segmentation Dataset, which contains information about 200 mall customers, including their age, annual income, and spending score. The goal is to segment these customers into groups with similar traits.

#Dataset

The dataset used in this project is Mall_Customers.csv, which contains the following attributes:

CustomerID: Unique ID assigned to each customer.
Gender: Gender of the customer (Male/Female).
Age: Age of the customer.
Annual Income (k$): Annual income of the customer in thousands of dollars.
Spending Score (1-100): A score assigned to the customer based on their spending behavior, with 1 being the lowest and 100 being the highest.
Project Workflow

#Data Exploration and Preprocessing:

Loaded and explored the dataset to understand its structure.
Performed basic exploratory data analysis (EDA) to examine the distribution of features like age, income, and spending score.
Checked for any missing values and ensured the dataset is clean and ready for clustering.

#Data Visualization:

Visualized the distribution of customer age, gender, annual income, and spending score to gain insights.
Used pair plots and histograms to explore relationships between features.

#Clustering with K-Means:

Applied the K-Means clustering algorithm to segment customers into distinct groups.
Used the Elbow Method to determine the optimal number of clusters.
Visualized the clusters using scatter plots to highlight the differences between customer segments.

#Results Interpretation:

Analyzed each cluster to interpret the characteristics of the customer segments.
Identified groups with high/low spending scores, varying income levels, and different age groups.

#Key Features

K-Means Clustering: The project uses K-Means clustering to segment customers into distinct groups based on their demographic data and purchasing behavior.
Elbow Method: This method was used to determine the optimal number of clusters for K-Means by plotting the inertia and looking for the "elbow point."
Visualizations: Scatter plots, histograms, and pair plots were used to explore the data and interpret the clustering results visually.
