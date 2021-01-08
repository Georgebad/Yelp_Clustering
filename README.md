# yelp-clustering
HOW IT WORKS?

 1.From yelp_academic_dataset_business.json keep only "Beauty and Spas" ,"shopping" and "Bars" businesses at Torronto with more than 10 reviews.
 
 2.From yelp_academic_dataset_reviews.json keep the reviews for the above businesses.
 
 3.Create TF-IDF from the above reviews.
 
 4.Cluster with:
 
                1)Kmeans
                
                2)Agglomerative clustering with single link,complete link,average link and ward link.
                
 5.Check result with confusion matrix,precision and recall.
 
 6.Create silhouette plot to decide the right number of clusters that K-means needs.
 
 7.Make again Confusion matrix to check results
 
 
