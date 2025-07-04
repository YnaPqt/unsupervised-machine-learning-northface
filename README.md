 # PROJECT Unsupervised Machine Learning

## The North Face ecommerce

Company's Description 📇

The North Face is an American outdoor recreation product company, founded in 1968 to supply climbers. The North Face produces clothing, footwear, and outdoor equipment. By the late 1990s customers had expanded beyond outdoor enthusiasts and in the 2000s it became a fashion style symbol.
Project 🚧

The marketing department would like to take advantage of machine learning solutions to boost online sales on the website : https://www.thenorthface.fr/

They have identified two major solutions that could have a huge effect on the conversion rates :

Deploying a recommender system that will allow to suggest additionnal products to users, that are similar to the items they are already interested in. The recommendations could be materialized by a "you might also be interested by these products..." section that would appear on each product page of the website.
Improving the structure of the products catalog thanks to topic extraction. The idea is to use unsupervised methods to challenge the existing categories : is it possible to find new categories of product that would be more suitable for the navigation on the website ?

## Goals 🎯

The project can be cut into three steps :

 1. Identify groups of products that have similar descriptions.

 2. Use the groups of similar products to build a simple recommender system algorithm.

 3. Use topic modeling algorithms to automatically assess the latent topics present in the item descriptions.

## Deliverable 📬

To complete this project:

1. Train at least one clustering model on the corpus and display wordclouds describing the clusters
2. Develop a simple python code that allows a user to type the id of a product he's interested in, and then get a list of similar items
3. Train at least one TruncatedSVD model on the corpus and display wordclouds describing the latent topics

