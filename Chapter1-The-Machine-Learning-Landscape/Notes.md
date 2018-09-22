### Some unsupervised learning algorithm
- Clustering
  - K-means
  - Hierachical Clustering Analysis (HCA)
  - Expectation Maximization
- Visualization and Dimension Reducation
  - PCA
  - Kernel PCA
  - Local linear embedding
  - t-distribution Stocastic Neighbour Embedding (t-SNE)
- Association Rule
  - Apiori
  - Ecalt

### Instance-Based vs Model-Base Learning
- Instance based. Make predictions based on instances. E.g., KNN will predict the label of an unseen instance based on existing ones. Or rote-learner, which can only predict an instance when it already has exactly the same one. Can also call this kind of learning as Memory-based, Exemplar-based , Case-based, Experience-based
- Model based. Learn a model (more straghtforward, a formula) to map features of an instance X to some kinda output. E.g., linear regression or neural network. The model is supposed to summarize the features of all observed instances. So after the model is built, those instances are not useful.

### Main challenges of ML
1. Not enough training data. According to my experiences, enough training data is much better than complex models.
2. Nonrepresentative training data. The training data are already biased. It has a different distribution from the test set or the real problem.
3. Poor quality data. Titanic dataset has lots of problems, e.g, missing data or wrong data or outliers.
4. Irrelevant features. Some features won't help prediction, but how to find them is a problem. Some problems are not linear, so it is hard to check whether 1 feature is relevant or not. Sometime,s combination of features which seems irrelevant can be a very good indicator.
5. Overfitting and underfitting. The former is caused by lack of data, and the latter happens when models can't fit the data well, e.g., too simple to capture the rules of data.

### No free lunch theorem

  