# PRODIGY_ML_02_KMEANS

![image](https://github.com/lekshmiij/PRODIGY_ML_02_KMEANS/assets/141242851/635ab0fa-b30c-4c80-b453-c5b12133d724)

#### Importing Libraries
The following libraries are imported for the implementation:
* numpy and pandas for data manipulation and numerical operations.
* matplotlib.pyplot and seaborn for data visualization.
* KMeans from sklearn.cluster for implementing the K-means clustering algorithm.
* StandardScaler from sklearn.preprocessing for feature scaling.
#### Loading the Data
The dataset Mall_Customers.csv is loaded into a DataFrame named customer_data.
#### Understanding the Data
Basic data inspection and preprocessing steps are conducted:
* The first few rows of the dataset are displayed using customer_data.head().
* The shape of the dataset is checked using customer_data.shape.
* Information about the dataset is obtained using customer_data.info().
* Missing values are checked using customer_data.isnull().sum().
#### Feature Selection
The features 'Annual Income' and 'Spending Score' are selected for clustering
#### Feature Scaling
The selected features are scaled to standardize the data
#### Determining the Number of Clusters
The optimal number of clusters is determined using the Elbow method, which involves plotting the Within Clusters Sum of Squares (WCSS) for different numbers of clusters
#### Training the K-means Clustering Model
The K-means model is trained with 5 clusters
The model returns a label for each data point based on their cluster.
#### Visualizing the Clusters
The clusters are visualized using a scatter plot. Different colors are used to represent different clusters, and the centroids of the clusters are marked in black

### About Dataset
Each row represents an individual customer with various attributes. The columns in the dataset are as follows:

* CustomerID: A unique identifier for each customer.
* Gender: The gender of the customer (Male/Female).
* Age: The age of the customer.
* Annual Income (k$): The annual income of the customer in thousand dollars.
* Spending Score (1-100): A score assigned by the mall based on customer spending behavior and loyalty (ranging from 1 to 100).
