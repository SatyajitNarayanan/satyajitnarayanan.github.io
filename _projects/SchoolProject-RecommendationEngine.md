---
title: "Recommendation Engine"
excerpt: "A system to recommend movies based on past user behavior & other users <br/><img src='/images/Recomm.jpg'>"
date: 2018-12-03
collection: projects
---

## Problem:
To create a recommendation engine that predicts the likeliness of a user liking a movie based on past user behavior and data on movies

### Data Used:
* The MovieLens dataset (https://grouplens.org/datasets/movielens/)
* Collected by the GroupLens Research Project at the University of Minnesota. It consists of:
  * 100,000 ratings (1-5) from 943 users on 1682 movies
  * Demographic info for the users
  * Genre information of movies

## Approach:
There are broadly two types of recommender engines – Content Based and Collaborative Filtering
* Content Based algorithms 
* Collaborative Filtering algorithm: Further, there are 2 types of collaborative filtering algorithms:
  * User-User Collaborative filtering 
  * Item-Item Collaborative filtering

* Predictions are made using Collaborative Filtering method for both:
  * Existing Users
  * New User

## Features incorporated

Hybrid prediction score
* (1- α) x User Prediction + α x Movie Prediction


Links:
* [Jupyter notebook](https://bit.ly/2ILJYcL)
* [Github](https://github.com/SatyajitNarayanan/Recommendation-Engine)


A video showing its working:

[![Recommendation Engine Working](http://img.youtube.com/vi/gARLtNfgFmQ/0.jpg)](https://www.youtube.com/embed/gARLtNfgFmQ)
