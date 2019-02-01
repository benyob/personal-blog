---
author: "Ayoub Benali Amjoud"
date: 2017-09-10
title: Collaborative Filtering and Recommender Systems
best: true
---

![image](/img/brought.jpeg)

Recommendation systems recommend items such as products or services to users. This is usually done on the basis of evaluations (collaborative filter) or of item properties (content-based filter).


The basic idea of a recommendation system is to recommend products such as books, services or places of interest or other so-called items to an active user. Based on information about the user, the items and, if necessary, other data, it is determined to what extent an item corresponds to the user's taste. This means that the system calculates a predicted value assignment of items for the active user, from which a list of recommendable items is usually generated for the active user.

## Types of recommendation systems

Basically, a distinction is made between individual and collaborative recommendation systems. Individual systems only determine recommendable items on the basis of information about the active user. This is often done using attributes that describe the items, which is why these systems are also called content-based recommenders. Attributes of items can be product properties or the price, for example. For the realization of a content-based recommendation system, for example, a rule system can be used which recommends items based on explicitly selected or implicitly learned user profile attributes. This category also includes text-based approaches that analyse the occurrence of certain terms in documents and compare them with user interests.

The second important category is collaborative filtering (CF). Other users are also taken into account in the recommendation. This is done by rating the users for items, e. g. on a scale from 1 to 5, with two variants: user- or memory-based (also called user-based CF) or item- or model-based (also called item-based CF) collaborative filtering. The latter method determines the similarity between two items calculated from the evaluations as a model, which offers advantages with regard to the performance of recommendation generation.

The recommendation process for memory-based collaborative filters consists of two basic steps:
**1.** calculating a set of users who have previously rated similarly to the active user (neighborhood),
**2.** selecting items that the active user has not yet rated, but have been rated as recommendable in their neighborhood.
To calculate the neighborhood in step 1, the evaluations of the active user are compared with those of the other users in the system. For this purpose, various similarity measures are suggested in the literature, e. g. cosine of the angle of the evaluation vectors, Euclidean distance, or Pearson-Spearman correlation.

A basic problem of CF is the cold start problem, i. e. the system cannot recommend good recommendations for new users or items, which is easier to alleviate with content-based filters. CF, on the other hand, can also generate better cross-genre recommendations, while content-based filters can be overspecialized to create a so-called portfolio aspect, i. e. recommended items are very similar to those already known.


**to be continued ...**
