# Crypto Clustering Challenge

This assignment involved loading and preparing data for cryptocurrencies affected by 24-hour or 7-day price change analysis and finding the optimal values for k with their inertia values. Cryptocurrencies are digital tokens. They are a type of digital currency that allows people to make payments directly to each other through an on-line system. 

Clustering analysis or clustering is the task of grouping a set of objects in such a way that objects in the same group are more similar to each other than to those in other groups. PCA is a statistical procedure that allows you to summarize the information content in large data tables by means of a smaller set of "summary indices" that can be more easily visualized and analyzed.

I imported the required libraries and dependencies using Python and unsupervised learning. I created dataframes, line charts, and scatter plots to visualize the dataset to determine Clustering and Principal Component Analysis(PCA). In addition, I used K-Means a clustering algorithm used in unsupervised machine learning for the original scaled data and PCA data to determine the optimal k values. I added crypto names to indentify crytocurrencies. I used hvplot to create two line charts with their inertia values and optimal k values using the elbow method algorithm. Also, I used hvplot to create two scatter plots with their data. Along with the visualizations, I was able to compare the results to answer the questions provided in jupyter notebook.

• Module 19 Challenge Citations:

Website Citation: https://bootcampspot.instructure.com/courses/4938/assignments/61916?module_item_id=1077449

'Title:<Crypto_Clustering.ipynb> 'Author:Qasim Khilji 'Date:<2024> 'Code Version:<1.0> 'Availability:https://github.com/mqkhilji/CryptoClustering/blob/main/Crypto_Clustering.ipynb

'Title:<Crypto_Clustering.ipynb> 'Author:Brandon Knox 'Date:<2024> 'Code Version:<1.0> 'Code:elbow_plot = elbow_df.hvplot.line(x="K", y="Inertia", title="Elbow Curve", xticks=k)
elbow_plot

