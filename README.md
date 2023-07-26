# Customer-Segmentation

This code demonstrates a customer segmentation method using the K-Means clustering technique. It allows businesses to group their customers based on two important features: "Annual Income" and "Spending Score." The K-Means algorithm is employed to partition the customers into distinct clusters, each characterized by similar spending behavior and income levels.

The process starts with loading the customer data from a CSV file and performing exploratory data analysis (EDA). EDA involves inspecting the data's structure, checking for missing values, and understanding its basic statistics.

Next, the optimal number of clusters is determined by utilizing the Elbow Method. This technique helps to identify the appropriate number of clusters that best represent the underlying patterns in the data. The Within-Cluster Sum of Squares (WCSS) is computed for different numbers of clusters, and a plot is generated to identify the "elbow point," indicating the optimal number of clusters (in this case, 5 clusters).

After identifying the optimal number of clusters, the K-Means algorithm is trained using this number of clusters. The model clusters customers based on their "Annual Income" and "Spending Score" features. It then assigns each customer to one of the five clusters based on their similarity to the cluster centroids.

Moreover, the code allows for user input to predict the cluster that a new customer belongs to. By providing both the "Annual Income" and "Spending Score," the model predicts the most suitable cluster, revealing insights into which customer segment the individual is likely to fall into.

Finally, the clusters and their respective centroids are visualized in a scatter plot. Each cluster is represented by a distinct color, and its corresponding label is displayed at the centroid location. This visual representation helps businesses understand the distinct customer groups and their characteristics, enabling them to tailor their marketing strategies, promotions, and services to cater to the specific needs of each cluster. Overall, this segmentation approach can enhance customer understanding and aid businesses in making data-driven decisions to optimize customer satisfaction and improve overall performance.
