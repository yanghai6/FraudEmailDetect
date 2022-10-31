# Fraud Email Detection in Enron

* Enron was one of the largest company in the U.S. in 2000, but went bankrupt in 2002 because fraud. In order to find out employees involved in the fraud, utilize maching learning and natural language processing algorithm to analyze the public email dataset of Enron.

* Use Latent Dirichlet Allocation (LDA) to split emails into 25 topics and use sentiment score to find the topic with the most negative emtion.

* Based on the LDA model, analyze how the topics vary by time and by person and use dynamic topics model(DTA) to further investigate topics in different years.

* Use word2vec to solve the drawback of the LDA model using bag-of-words and ignoring syntactic and semantic word relationships.

* Use multidimensional scaling on a matrix of how often each pair of people talks to each other. Construct network analysis and compute degree centrality as well as betweeness centrality to find significant employees in clusters.
