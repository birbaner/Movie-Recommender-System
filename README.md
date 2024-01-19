# Movie-Recommender-System
Using Neural Network
Overview
This project implements a movie recommender system using a Neural Network, specifically focusing on collaborative filtering with matrix factorization. The MovieLens 20M Dataset, provided by GroupLens, is used for training and testing the model.

Dataset
The dataset contains 20,000,263 ratings across 27,278 movies created by 138,493 users from January 9, 1995, to March 31, 2015. To manage the dataset's size, a subset of users who rated at least 20 movies each is selected randomly.

Code Breakdown
The code involves preparing user-item interaction matrices for training, validation, and test sets. Key steps include initializing matrices, iterating over the dataset to assign ratings, and calculating sparsity for each set. The sparsity percentage is printed to evaluate the density of rated items.

Matrix Factorization
The project incorporates matrix factorization for collaborative filtering. This technique decomposes the user-item interaction matrix into lower-dimensional matrices representing users and items, known as user and item embeddings.

Neural Network Architecture
The neural network architecture includes input layers for users and movies, embedding layers for transforming user and movie IDs into dense vectors, flattening layers, and a dot product layer for capturing interactions.
