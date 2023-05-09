# CryptoClustering
## Module 19

### Background</br>
In this challenge, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
</br></br>

<i>To receive all points, i guarantee my code has all of the following: </i></br>
* Code the elbow method algorithm to find the best value for k. Use a range from 1 to 11.</br>
* To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.</br>
* Answer the following question: What’s the best value for k?</br>
* Initialize the K-means model with four clusters by using the best value for k.</br>
* Fit the K-means model by using the original data.</br>
* Predict the clusters for grouping the cryptocurrencies by using the original data. Review the resulting array of cluster values.</br>
* Create a copy of the original data, and then add a new column of the predicted clusters.</br>
* Using hvPlot, create a scatter plot by setting x="price_change_percentage_24h" and y="price_change_percentage_7d". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.</br>
* Create a PCA model instance, and set n_components=3.</br>
* Use the PCA model to reduce the features to three principal components. Then review the first five rows of the DataFrame.</br>
* Get the explained variance to determine how much information can be attributed to each principal component.</br>
* Answer the following question: What’s the total explained variance of the three principal components?</br>
* Create a new DataFrame with the PCA data. Be sure to set the coin_id index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame.</br>
* Code the elbow method algorithm, and use the PCA data to find the best value for k. Use a range from 1 to 11.</br>
* To visually identify the optimal value for k, plot a line chart of all the inertia values computed with the different values of k.</br>
* Answer the following questions: What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data?</br>
* Initialize the K-means model with four clusters by using the best value for k.</br>
* Fit the K-means model by using the PCA data.</br>
* Predict the clusters for grouping the cryptocurrencies by using the PCA data. Review the resulting array of cluster values.</br>
* Create a copy of the DataFrame with the PCA data, and then add a new column to store the predicted clusters.</br>
* Using hvPlot, create a scatter plot by setting x="PC1" and y="PC2". Color the graph points with the labels that you found by using K-means. Then add the crypto name to the hover_cols parameter to identify the cryptocurrency that each data point represents.</br>
* Create a composite plot by using hvPlot and the plus sign (+) operator to compare the elbow curve that you created from the original data with the one that you created from the PCA data.</br>
* Create a composite plot by using hvPlot and the plus (+) operator to compare the cryptocurrency clusters that resulted from using the original data with those that resulted from the PCA data.</br>
* Answer the following question: Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means?</br>
* Place imports at the top of the file, just after any module comments and docstrings, and before module globals and constants.</br>
* Name functions and variables with lowercase characters, with words separated by underscores.</br>
* Follow DRY (Don't Repeat Yourself) principles, creating maintainable and reusable code.</br>
* Use concise logic and creative engineering where possible.</br>
* Submit a link to a GitHub repository that’s cloned to your local machine and that contains your files.</br>
* Use the command line to add your files to the repository.</br>
* Include appropriate commit messages in your files.</br>
* Code Comments</br>
* Be well comment cise, relevant notes that other developers can understand.</br>
