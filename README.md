# machine_learning_project-unsupervised-learning

## Project Goal

Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

### Process

In this project, I will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about  clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories.You can find this data set on kaggle-https://www.kaggle.com/datasets/binovi/wholesale-customers-data-set

The unsupervised_leaarning_project.ipynb has the following steps 

-	Exploratory data analysis and pre-processing: The data set was explored to see if any cleaning was required, the data set was fairly clean but outliers were handled using capping technique in order to maintain the size of the data set as it is a small data set with only 440 rows of data
-	Unsupervised learning:  k-means clustering, hierarchical clustering, and principal component analysis (PCA) were conducted as a means to identify patterns and group similar data points together. various methods such as elbow rule,silhouette score and dendogram were used to determine the optimal number of clusters and communicate the insights gained through data visualization.

As mentioned above using the technique of capping to deal with outliers you will find a wholsale_capped.csv which stores the new data so as to have a copy of the original dataset for future use.

### Challenges

Visualization of the clusters was difficult as the data set has 6 features .PCA allows us to visualize the clusters but at the cost of loosing insight into the features and making an accurate interpretation based on that is difficult. 

