# Movie Recommendation System using Collaborative Filtering

## Overview

This project implements a Movie Recommendation system using Collaborative Filtering techniques, leveraging FastAI and PyTorch. The goal is to understand and apply the key concepts behind collaborative filtering, including embeddings, to build an effective recommendation engine.

### Key Concepts

In this project, the following concepts are explored:
	•	Embeddings: Learn how to represent high-dimensional data in lower-dimensional spaces, allowing efficient similarity computations between users and movies.
	•	Collaborative Filtering: Understand the power of collaborative filtering to make personalized recommendations based on user-item interactions.
	•	Collab Learner from Scratch: Learn how to build a recommendation model from scratch using FastAI’s CollabLearner and understand the inner workings of the collaborative filtering algorithm.

### Project Details
	•	Data: MovieLens dataset is used for training the model, consisting of ratings, user information, and movie data.
	•	Tech Stack:
	•	FastAI: To implement the collaborative filtering model and perform deep learning tasks.
	•	PyTorch: For building and training the neural network models.
	•	Model: A collaborative filtering model built using CollabLearner from FastAI, which learns user-item embeddings and makes movie recommendations based on these embeddings.

### Features
	•	Data Preprocessing: Prepare the MovieLens dataset for training by cleaning and normalizing the data.
	•	Model Training: Use FastAI’s CollabLearner to train a model that learns user and movie embeddings.
	•	Recommendation : find the top movie recommendations for users based on the learned embeddings.
	•	Evaluation: Assess the performance of the model using appropriate metrics such as RMSE (Root Mean Square Error) to measure prediction accuracy.

### Getting Started
	1.	Clone this repository:

git clone https://github.com/Ali-Alshaikh/Movie-Recommendation-DeepLearning.git
cd Movie-Recommendation-DeepLearning


	3.	Run the notebook MovieRecommendation.ipynb to start the model training and make predictions.

### Future Work
	•	Implement a more complex model that includes additional features such as movie genres and user demographics.
	•	Improve the model’s performance with advanced techniques like matrix factorization and hybrid filtering.

### Acknowledgments
	•	MovieLens dataset: https://grouplens.org/datasets/movielens/
	•	FastAI and PyTorch for providing powerful frameworks for deep learning.

Feel free to contribute or open issues if you have suggestions or improvements!

# Happy Ramadan 🌙
