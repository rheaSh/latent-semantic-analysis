# latent-semantic-analysis
Clustering on dimensionally reduced feature vectors to figure out semantically similar documents. IPython Notebook
Numpy, Pandas, Sklearn are used

For each document, tf-idf values are found for each word in thee overall vocabulary. 
This high dimensional feature vector is then reduced to having only 2 dimensions.
cosine similarity is used to compare similarity of any two documents.
Finally, by way of kmeans clustering, similar valued documents are clubbed together and plotted.
