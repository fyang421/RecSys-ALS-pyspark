# RecSys_ALS_pyspark

This project builds an alternating least square (ALS) matrix factorization recommendation system implemented with Spark ML.
The ALS model was trainined on the MovieLens 27,000,000 movie rating dataset. 

v1: Reconstruct original rating. Evaluate model using RMSE.

v2: Transform orginal rating to binary rating, and then reconstruct binary rating. Added popularity based recommendation. Evaluate model using RMSE, MAP, Precision@k and NDCG@k

