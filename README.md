# Netflix Movies and TV Shows Clustering
Project Summary: 

We used Netflix Movies and TV Shows dataset which includes several features like Show id, Type of content, Title ,Name of the Director(s),Name of the Cast(s),Country,Date added,Release year,Rating,Duration,Type of Genre and Description.There were around 7787 records and 12 attributes in the dataset. The process followed:

1. Analysed the data- The number of rows and columns it had,type of the features presented,the kind of data each particular feature had,checked for duplicated or missing values.
2. Data manipulation- Checked for outliers and null values and fiixed it with the necessary operations.
3. Data Visualization - plotted various graphs and like Percentage of Movies and TV Shows present,Monthly count for the type of Content,Top 10 directors based on the number of shows they have directed,Top 10 Actors based on the number of shows they have worked in, Countries producing shows,the duration of movies and TV Shows and etc.Also plotted heatmap to find the correlation between different features.
4. Data Pre-processing and feature selection- Dropped the unnecessary columns and rows.Performed Text Data Processing like contraction,removing urls,punctuations and stopwords.Also performed tokenization and vectorization.
5. Model Implementation - 2 model have been created with different ML Algorithms:K-Means Clustering and Hierarchical Clustering.
6. K-Means Clustering:It is an iterative algorithm that divides the unlabeled dataset into k different clusters in such a way that each dataset belongs only one group that has similar properties.
7. K-means clustering have some challenges which are a predetermined number of clusters, and it always tries to create the clusters of the same size. To solve these two challenges, we can opt for the hierarchical clustering algorithm because, in this algorithm, we don't need to have knowledge about the predefined number of clusters.
8. Davies-Bouldin Index is used for the evaluation of the models.
9. Davies-Bouldin Index measures the size of clusters against the average distance between clusters.
10. Using Cosine similarity a recommendation function is created to provide the title of shows which are similar in nature.
