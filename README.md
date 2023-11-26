# Amazon-Product-Recommendation-System

# Context:
Today, information is growing exponentially with volume, velocity and variety throughout the globe. This has lead to information overload, and too many choices for the consumer of any business. 
It represents a real dilemma for these consumers and they often turn to denial. 
E-commerce websites like Amazon, Walmart, Target and Etsy use different recommendation models to provide personalized suggestions to different users. 
Amazon, for example, is well-known for its accurate selection of recommendations in its online site. 
Amazon's recommendation system is capable of intelligently analyzing and predicting customers' shopping preferences in order to offer them a list of recommended products. 
Amazon's recommendation algorithm is therefore a key element in using AI to improve the personalization of its website. For example, one of the baseline recommendation models that Amazon uses is item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real-time.

# Objective:
You are a Data Science Manager at Amazon, and have been given the task of building a recommendation system to recommend products to customers based on their previous ratings for other products. 
You have a collection of labeled data of Amazon reviews of products. 
The goal is to extract meaningful insights from the data and build a recommendation system that helps in recommending products to online consumers.

# Dataset:
1) Rank Based Recommendation System
2) Collaborative Filtering Recommendation System
  a) User-User Similarity-based Recommendation System
  b) Item-Item Similarity-based Recommendation System
3) Model-Based Collaborative Filtering - Matrix Factorization

# Dataset:
The Amazon dataset contains the following attributes:

1) userId: Every user identified with a unique id
2) productId: Every product identified with a unique id
3) Rating: The rating of the corresponding product by the corresponding user
4) timestamp: Time of the rating. We will not use this column to solve the current problem
