# Customer-Segmentation-KMeans
Customer segmentation using K-Means clustering, Python and Scikit-learn.
Customer Segmentation Using K-Means Clustering
A Machine Learning project that groups mall customers based on their annual income and spending scores using K-Means clustering.

Objective
To segment customers into meaningful groups using unsupervised machine learning and identify patterns in their spending behavior.

Dataset
* Dataset: Mall Customers
* Total records: 200
* Features used:
* Annual Income (k$)
* Spending Score (1-100)

Technologies Used
* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Methodology
1. Data loading and exploration
2. Feature selection
3. Data standardization using StandardScaler
4. Optimal cluster selection using the Elbow Method
5. Model evaluation using Silhouette Score
6. Customer segmentation using K-Means
7. Visualization and interpretation

Model Results
* Algorithm: K-Means Clustering
* Number of clusters: 5
* Silhouette Score: 0.555

Customer Segments
| Cluster | Customer Segment                 | Count |
| ------- | -------------------------------- | ----: |
| 0       | Average income, average spending |    81 |
| 1       | High income, high spending       |    39 |
| 2       | Low income, high spending        |    22 |
| 3       | High income, low spending        |    35 |
| 4       | Low income, low spending         |    23 |

Key Insights
* Customers show different spending patterns across income groups.
* High-income customers may have either high or low spending scores.
* Segmentation can help businesses plan personalized marketing campaigns and customer engagement strategies.

Future Scope
* Include additional customer attributes such as age and gender.
* Compare K-Means with other clustering algorithms.
* Develop an interactive dashboard for customer segmentation.
* Test cluster stability on larger datasets.

How to Run
1. Clone this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Load the dataset and run all notebook cells.

