# E-commerce-Personalization
# Customer Segmentation using K-means Clustering and PCA

This project involves customer segmentation based on purchasing behavior within an e-commerce dataset using K-means clustering and Principal Component Analysis (PCA). The goal is to identify distinct groups of customers with similar preferences and behaviors to enable personalized marketing strategies and recommendations.

## Steps

1. **Data Preparation:**
   - Load the Online Retail dataset.
   - Preprocess the data by handling missing values and removing canceled orders.

2. **Feature Engineering:**
   - Aggregate data by CustomerID and calculate relevant features such as total spending, order frequency, and quantity.

3. **Dimensionality Reduction with PCA:**
   - Standardize the features.
   - Apply PCA to reduce the dimensionality of the data while retaining informative features.

4. **Determining Optimal Number of Clusters:**
   - Use the Elbow Method to determine the optimal number of clusters for K-means clustering.

5. **K-means Clustering:**
   - Perform K-means clustering to assign each customer to a cluster based on their feature values.

6. **Cluster Profiling (optional):**
   - Profile each cluster to identify characteristics such as average spending and purchase frequency.

7. **Visualization:**
   - Visualize the clusters using scatter plots in the reduced feature space.

## How to Use

1. **Clone Repository:**
git clone https://github.com/ahmed-eldesoky284/E-commerce-Personalization.git

2. **Install Dependencies:**
pip install pandas scikit-learn matplotlib

3. **Run the Code:**
- Ensure that the `Online Retail.xlsx` file is in the same directory as the Python script.
- Run the Python script `main.py`.
- View the generated scatter plot to visualize the clusters.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
