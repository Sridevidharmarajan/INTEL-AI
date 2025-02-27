K-Means Clustering on Iris Dataset

Overview
This project applied K-Means clusteringto the Iris dataset to identify natural groupings among the flower samples. The dataset consists of sepal and petal features, which are used to classify flowers into clusters without prior labels.

Features
- Data Preprocessing: Handles missing values and standardizes the dataset.
- Elbow Method: Determines the optimal number of clusters.
- K-Means Clustering: Groups data points based on feature similarities.
- Silhouette Score Evaluation: Measures the clustering performance.
- Cluster Visualization: Displays the clustered data in a 2D scatter plot.

Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sridevidharmarajan/kmeans-iris.git
   ```
2. Navigate to the project directory:
   ```bash
   cd kmeans-iris
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
Usage
1. Run the script:
   ```bash
   python kmeans_iris.py
   ```
2. The script will:
   - Load and preprocess the Iris dataset.
   - Apply K-Means clustering.
   - Determine the optimal number of clusters.
   - Visualize the results.

Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

Results
The model identifies clusters based on flower features and visualizes them in a scatter plot. The optimal number of clusters is determined using the Elbow Method and validated with the Silhouette Score.

License
This project is licensed under the MIT License.

Author
[Sridevi](https://github.com/sridevidharmarajan)

