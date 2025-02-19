# Customer Segmentation Analysis Using K-Means Clustering

### Overview
This project demonstrates customer segmentation using the K-Means clustering algorithm on the **Mall Customers Dataset**. Customer segmentation helps businesses understand customer demographics and spending patterns, allowing for personalized marketing strategies and better customer engagement.

### Dataset
The dataset contains the following key information about mall customers:

| **Column**         | **Description**                                    |
|--------------------|----------------------------------------------------|
| **CustomerID**      | Unique identifier for each customer                |
| **Gender**          | Male or Female                                     |
| **Age**             | Age of the customer                                |
| **Annual Income**   | Customer's annual income (in $k)                   |
| **Spending Score**  | A score assigned by the mall based on spending behavior |

### Project Structure

- **Exploratory Data Analysis (EDA)**: Visualizations explore customer demographics, including age distribution, income levels, and spending score distribution. A correlation matrix is generated to understand feature relationships.

- **Feature Scaling**: Features (Age, Annual Income, Spending Score) are scaled to ensure consistent ranges before applying clustering.

- **K-Means Clustering**: The K-Means algorithm segments customers into distinct groups. The optimal number of clusters is determined using the Elbow Method.

- **Cluster Visualization**: Clusters are visualized in 2D space using PCA (Principal Component Analysis), making it easier to interpret the customer segments.

- **Cluster Insights**: Analysis of each cluster to extract key characteristics, such as average age, income, and spending habits, along with recommendations for business strategies.

### Key Features
- **Elbow Method**: Used to determine the optimal number of clusters based on within-cluster sum of squares (WCSS).
- **Customer Segmentation**: Segmentation of customers into clusters based on age, income, and spending score.
- **Cluster Analysis**: Detailed insights into the customer clusters, including statistics and behaviors.
- **Visualization**: Comprehensive visualizations using PCA, Seaborn, and Matplotlib for both EDA and cluster interpretation.

### Insights and Recommendations
The clustering process identified **five distinct customer segments**, each with unique characteristics:

| **Cluster** | **Key Characteristics**                                    | **Business Strategy**                                    |
|-------------|-------------------------------------------------------------|----------------------------------------------------------|
| **Cluster 0**  | Young customers with moderate income and spending scores  | Offer special deals to engage them more effectively       |
| **Cluster 1**  | High-income customers with high spending scores          | Focus on premium product offerings and exclusive rewards  |
| **Cluster 2**  | Older customers with moderate income and lower spending  | Target with offers that improve retention                 |
| **Cluster 3**  | Low-income customers with low spending scores            | Use discount campaigns and loyalty programs               |
| **Cluster 4**  | Middle-aged customers with high income and moderate spending | Increase engagement through personalized recommendations  |

### Future Work
- Extend the analysis by including additional features such as customer behavior and purchase history.
- Experiment with alternative clustering techniques like DBSCAN or hierarchical clustering for more nuanced segmentation.
- Develop a **Power BI dashboard** to provide an interactive experience for exploring customer segments and insights.

### Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project and expand its capabilities.

