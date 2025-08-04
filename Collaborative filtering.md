# Collaborative Filtering
## What is Collaborative Filtering?
- Collaborative filtering is a technique used in recommender systems to predict a user's interests by analyzing preferences from many users.

## What are the key components of Collaborative Filtering?

- User-Item Interaction
- Similarity Measurement
- Recommendation Generation
- Types of Collaborative Filtering

---

## What is User-Item Interaction?

- User-item interaction refers to the data collected from users based on their engagement with items.

## What are examples of User-Item Interaction?

- A user rating a movie
- A user purchasing a product
- A user clicking on a video
- A user bookmarking an article

---

### What is Similarity Measurement?

- Similarity measurement quantifies how alike users or items are based on their interaction patterns.

### What are common similarity metrics?

- Cosine Similarity
- Pearson Correlation
- Jaccard Index
#### What is Cosine Similarity?

- Cosine similarity measures the cosine of the angle between two vectors representing user or item profiles.

#### What is Pearson Correlation?

- Pearson correlation measures the linear relationship between two variables, often used to compare rating patterns.

#### What is Jaccard Index?

- Jaccard index measures similarity between two sets by dividing the size of their intersection by the size of their union.

---

## What is Recommendation Generation?

- Recommendation generation is the process of predicting and suggesting items to users based on similarity scores.

- What are methods of Recommendation Generation?
  - Predicting ratings
  - Ranking items
  - Filtering out previously seen items

---

## What are the Types of Collaborative Filtering?

- User-Based Collaborative Filtering
- Item-Based Collaborative Filtering
- Model-Based Collaborative Filtering

---

### What is User-Based Collaborative Filtering?
- User-based collaborative filtering finds users similar to the target user and recommends items liked by those similar users.
   - What are the steps in User-Based Collaborative Filtering?
        - Identify similar users
        - Aggregate their preferences
        - Recommend items they liked
---

### What is Item-Based Collaborative Filtering?

- Item-based collaborative filtering finds items similar to those the user has interacted with and recommends those similar items.

#### What are the steps in Item-Based Collaborative Filtering?

- Identify items similar to those the user liked
- Score items based on similarity
- Recommend top-scoring items

---

### What is Model-Based Collaborative Filtering?

- Model-based collaborative filtering uses machine learning models to learn user-item interaction patterns and make predictions.

#### What are common models used?

- Matrix Factorization (e.g., SVD)
- Neural Networks
- Clustering Algorithms
##### What is Matrix Factorization?

- Matrix factorization decomposes the user-item interaction matrix into lower-dimensional representations to uncover latent features.

##### What are Neural Networks in Collaborative Filtering?

- Neural networks learn complex patterns in user-item interactions using layers of interconnected nodes.

