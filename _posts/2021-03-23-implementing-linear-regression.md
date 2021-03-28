---
layout: post
title: "Implementing Linear Regression"
categories: "Machine Learning"
tags:
  - "Machine Learning"
  - "Python"
---

Linear regression is perhaps one of the simplest of machine learning algorithms. In this post, I am going to show you how to implement this algorithm in python from scratch. We'll implement an API which is much similer to the SciKit Learn API. Before we go the implimentation part, let's first discuss the algorithm.
<!-- more -->

I want to keep this part short, so I am not going to answer questions like what is machine learning and what is superviced learning. You can look into other resources to find answer to this question. We'll jump stright into the algorithm.

The hypothesis function of linear regression algorithm is given by
$$h(x)=\[\sum_{i=0}{n}\theta_i x_i]$$
