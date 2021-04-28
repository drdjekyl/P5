# Client segmentation for Olist - Brasilian leader in e-commerce

Dataset: https://www.kaggle.com/olistbr/brazilian-ecommerce

Context/Scenario: Olist wants you to provide customer segmentation to its marketing team and use the segmentation in their daily communication campaigns.
Your objective is to understand the different types of users through their behaviour and personal data.

Problem: Find client segmentation to help marketing department

Methods:
1. Explore the 9 datasets
2. Merge the datasets
3. Extract pertinent features
4. Drop NA
5. EDA to understand clients behaviour
6. Feature engineering (Recency, Frequency, Value)
7. Standardisation
8. Sampling
9. Dimension reduction (tSNE, Isomap, PCA)
10. Clustering with KMeans, DBScan
11. Coordinate plot to interpret the results
12. Time stability of the clusters

Results:
1. Best segmentation obtained with Isomap and Kmeans: Silouhette coeff=0.73, Davies Bouldin=0.45
2. Clients distinguished by payment mode, number of items and prices
3. Stable clusters during 15 months (ARI > 0.8)

Libraries: Pandas, Numpy, Matplotlib, Scikit-learn
