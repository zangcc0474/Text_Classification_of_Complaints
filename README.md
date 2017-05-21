# Text Classification of Complaints about Traffic Conditions to The City of Boston

There are two main files:
1)  .travis.yml: To configure the Travis and set the environment for test
2)  hw4_starter_notebook.ipynb: The file containing the codes

The steps in the code:
1)  Data Cleaning
      - Load the data, visualize the class distribution. 
      - Clean up the target labels. Some categories have been arbitrarily split and need to be consolidated. 
2)  Model 1
      - Run a baseline multi-class classification model using a bag-of-word approach
      - Evaluate macro f1-score 
      - Visualize the confusion matrix. 
3)  Model 2
      - Improve the model using more complex text features, including n-grams, character n-grams and possibly domain-specific features.
4)  Visualize Results
      - Visualize results of the tuned model (classification results, confusion matrix, important features, example mistakes).
5)  Clustering
      - Apply LDA, NMF and K-Means to the whole dataset. 
      - Compare clusters or topics with some of the ground truth labels? 
      - Use ARI to compare the methods and visualize topics and clusters.
6)  Model 3
      - Improve the class definition for REQUESTTYPE by using the results of the clustering and results of the previous classification model. 
      - Re-assign labels using either the results of clustering or using keywords that you found during data exploration. The labels must be semantically meaningful.
      - Apply the topic modeling and clustering techniques to “other” category of the data to find possible splits of this class.
      - Report accuracy using macro average f1 score  
7)  Extra 
      - Use a word embedding representation like word2vec for step 3 and or step 6. 
