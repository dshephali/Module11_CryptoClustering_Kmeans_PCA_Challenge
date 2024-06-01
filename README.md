# Module11_Crypto_Kmeans_PCA_Challenge

In this challenge we classified crypto currencies according to price changes within 24 hours, 7 days, 14 days, 30 days, 60 days , 200 days and 1 year timeframe/intervals. We used Kmeans algorithm and PCA (Principal Component Analysis) to predict best k value, predict clusters, create plots, and determine weight for each feature under each component to evaluate which intervals had the most change or the least change in c 

Authors & Citation

Alberto Aigner's feedback for a couple of errors

Summary 
First you import libraries and dependencies, load data from the csv file, prepare the data by normalizing it using StandardScaler, find the best k value in the scaled data using elbow method, create Kmeans clusters based on the best value of k, fit the model, predict clusters and create a scatter plot. Next, perform a Principal Component Analysis using original scaled data and reduce the features to 3 principal components, find the best value of K using elbow method again , define number of clusters using the best value of k , predict the clusters and plot them. Lastly, determine the weight of each feature on each principal component i.e. PCA1, PCA1 and PCA3 and determine which features have the strongest positive or negative influence in each component.