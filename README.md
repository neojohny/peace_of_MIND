## News Recommendation with (deep) Neural Networks
### Introduction
Machine learning algorithms have been implemented in recommender systems broadly. One common method is collaborative filtering, where the system suggests a new product based on the user's interest by collection information from many other users.

News, on the other hand, is quite different from common e-commerce products since it happens in real time by nature, changes momentarily and also has a broad range of semantic meanings, making the coexistence matrix more sparse, hence harder for collaborative filtering models to work. 

This makes us explore more complex embedding methods and model architectures, like neural networks, to represent features and relationships between users and news contents for better recommendations. Specifically, we are exploring graph embeddings for both news contents and individual users and try to predict edges for recommendations. We are also exploring whether Knowledge Graph will help enhance model performance. 

### Approach:
* Collecting datasite with guidance on Mind methodology. Collecting baseline metrics for future comparison.
* Before going to deep learning, trying to explore innovative ideas within shallow learning to gain insights on the dataset.
* Beginning in embedding method search. Initial ideas are doc2vec embedding, sequence embedding and graph embeddings.
* Build neural network architecture for edge detection to solve the recommendation problems and compare results with shallow learning.
* Explore state of the art models and architectures like BERT, transformer and attention mechanisms to improve model performance.
