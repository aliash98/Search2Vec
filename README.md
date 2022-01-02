# Personalized Search2Vec

This repository is dedicated to my BSc Thesis in Computer Engineering at Sharif University of Technology

## Thesis Subject
Implementation of an effective personalized retrieval method for search engines based on the contents of queries and the background of users‘ behavior

## Supervisors
Prof. Abbas Hosseini and Prof. Hamid R. Rabiee
This project is one of [MLSys lab](https://mlsys.darkube.app/) projects.

## Abstract
Given a query as an input, retrieving and ranking items is critically important in e-commerce platforms. My project aims to propose and develop an effective personalized embedding-based retrieval method from scratch (with TensorFlow), to enhance users' experience. The main idea comes from Word2Vec, an NLP algorithm that has been broadened to Search2Vec for recommendation usages. Influenced by methods introduced in "Scalable Semantic Matching of Queries to Ads in Sponsored Search Advertising" by Mihajlo Grbovic et al., which is also known as "Search2Vec", this code learns the embedding space of search queries and available products (or product categories). Training a neural network based on the mentioned algorithms produces an embedding space that can effectively place related queries and items near each other. Moreover, user clustering, based on users' history of clicks, has been employed to personalize the results of our ranking method. Two datasets, one obtained from torob.ir (one of the largest Persian online shops), and the other from AOL (publicly available on Kaggle), are being used for experimenting.

# Technical Details
The skip-gram is implemented with Tensorflow, Pandas, NumPy and Scikit-learn.
Normalized Discounted Cumulative Gain (nDCG) and Mean Reciprocal Rank (MRR) is used to test the model.
Similarity Matrix is computed using users' clicks based on the idea discussed in "Employing Personal Word Embeddings for Personalized Search" by Jing Yao et al.
Spectral clustering has been employed to putting similar users into groups.

