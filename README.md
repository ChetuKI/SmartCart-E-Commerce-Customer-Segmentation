# SmartCart – E-Commerce Customer Segmentation

##  Project Overview

SmartCart is an E-Commerce Customer Segmentation project that uses 
Machine Learning and customer purchasing behavior to identify
different groups of customers.

The project analyzes customer demographics, income, purchasing
patterns, shopping channels, website visits, and other behavioral
attributes to discover meaningful customer segments.

##  Objective

The main objective of this project is to segment customers into
different groups based on their characteristics and purchasing
behavior.

These customer segments can help businesses understand their
customers and support data-driven marketing and business strategies.

##  Dataset

The dataset contains **2,240 customer records** with **22 original
features**, including:

- Customer ID
- Year of Birth
- Education
- Marital Status
- Income
- Number of Kids and Teenagers
- Customer Joining Date
- Recency
- Product purchase amounts
- Web, Catalog and Store purchases
- Website visits
- Complaints
- Campaign response

##  Project Workflow

1. Data Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Missing Value Handling
5. Feature Engineering
6. Categorical Feature Encoding
7. Feature Scaling
8. Dimensionality Reduction using PCA
9. Customer Segmentation using K-Means Clustering
10. Cluster Evaluation
11. Visualization and Customer Segment Analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- PCA
- K-Means Clustering

##  Feature Engineering

Additional features are created from the existing customer information,
including:

- **Age** – derived from `Year_Birth`
- **Customer_Tenure_Days** – calculated from the customer joining date

Missing values in the `Income` feature are handled using median
imputation.

##  Machine Learning

K-Means clustering is used to group customers based on their
characteristics and purchasing behavior.

The Elbow Method (WCSS) and Silhouette Score are used to evaluate
different numbers of clusters.

PCA is also used to reduce the dimensionality of the dataset and
visualize customer clusters.

##  Visualizations

The project includes visualizations for:

- Customer distributions
- Feature relationships
- Elbow Method
- Silhouette Score
- PCA projections
- 3D customer segmentation
- Cluster analysis

##  Key Outcome

The project demonstrates how unsupervised Machine Learning can be
used to discover customer segments from E-Commerce data and extract
meaningful patterns from customer behavior.

## 👨‍💻 Author

**Chetan Kallappa Ingali**
