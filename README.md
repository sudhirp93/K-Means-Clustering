## K-Means-Clustering

Objective: Predict the optimum number of clusters of the dataset and represent them graphically using Unsupervised ML model (K-Means)

Data Collection: Found the dataset on the internet named 'Iris' dataset, a structured one.

Data Preparation: Saved the dataset into dataframe and analyse the characteristics Min, max, std, IQR and median of it. Checked the null values if any present init. First I used lmplot from seaborn library and saw that some inbuilt clusters are already there, I just want to make them more accurate or reduce the noise. Here we have numerical dataset and convert them into clusters so I chose KMeans cluster algorithms here as per the objective.

Choose a Model and clusters: Choosed model is K-Means clustering (Unsupervised ML model). First I dropped the category column, and tried to find the optimum number of clusters using SSE also called 'Elbow plot' where I used kmeans.inertia which split the dataset those have equal variance and with the plot I could easily interpret the number of clusters is 3, because at 2 and 3 the value of SSE is decreased very sharply which means at this value we will get neat clusters

Train the Model: I recalled the model with the calcualted clusters and fit the model with given features and calculated the positions of centres and at last label the whole dataset with the predictions

Evaluate the Model: I used lmplot for the both dataset given and predicted one and I can easily interpret the difference between them, predicted model was better than the given and there was less noise also.

Make Predictions: After evaluating the model, I can use it to make clusters of othere values also
