# Online Shoppers Purchasing Intention Analysis

## Project Overview

This project involves analyzing an online shopper's purchasing intention dataset using machine learning techniques. The goal is to perform clustering on the dataset using K-means and Gaussian Mixture Model (GMM) algorithms, and to compare the performance of these clustering techniques based on various evaluation metrics.

## Dataset

The dataset used in this project is the "Online Shoppers Purchasing Intention" dataset. It contains information about online shopping sessions and whether a shopper made a purchase. The dataset includes 18 features such as:

- `Administrative`
- `Administrative_Duration`
- `Informational`
- `Informational_Duration`
- `ProductRelated`
- `ProductRelated_Duration`
- `BounceRates`
- `ExitRates`
- `PageValues`
- `SpecialDay`
- `Month`
- `OperatingSystems`
- `Browser`
- `Region`
- `TrafficType`
- `VisitorType`
- `Weekend`
- `Revenue` (target variable)

## Exploratory Data Analysis (EDA)

1. **Basic Information:**
   - Displayed the first few rows of the dataset.
   - Checked for missing values.
   - Obtained summary statistics for numerical columns.

2. **Distribution of Target Variable:**
   - Visualized the distribution of the target variable `Revenue`.

3. **Feature Distribution:**
   - Plotted histograms of numerical features, separated by the target variable.
   - Created a correlation matrix heatmap.

## Data Preprocessing

1. **Handling Missing Values:**
   - No missing values were detected.

2. **Encoding Categorical Variables:**
   - Applied one-hot encoding to categorical features.

3. **Scaling Numerical Features:**
   - Standardized numerical features using `StandardScaler`.

## Clustering Analysis

1. **K-means Clustering:**
   - Implemented K-means clustering algorithm.
   - Determined the optimal number of clusters using the elbow method.
   - Evaluated clustering performance using Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score.
   - Visualized clusters and cluster centers.

2. **Gaussian Mixture Model (GMM):**
   - Implemented GMM using the Expectation-Maximization (EM) algorithm.
   - Initialized parameters and trained the GMM model.
   - Evaluated clustering performance using Silhouette Score, Calinski-Harabasz Score, and Davies-Bouldin Score.
   - Visualized clusters and convergence.

## Results

- **K-means Clustering Metrics:**
  - Silhouette Score: `0.241`
  - Calinski-Harabasz Score: `1667.75`
  - Davies-Bouldin Score: `1.548`

- **GMM Clustering Metrics:**
  - Silhouette Score: `0.024`
  - Calinski-Harabasz Score: `782.82`
  - Davies-Bouldin Score: `3.120`

- **Visualizations:**
  - Scatter plots and pair plots were used to compare clustering results visually.

## Conclusion

Based on the evaluation metrics and visualizations, K-means clustering provided better performance for this dataset compared to GMM. K-means showed better-defined and more distinct clusters.

 
