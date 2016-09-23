---
layout: single
author_profile: false
permalink: /dm/
---

Welcome to the webpage for the Fall 2016 Data Mining course. Below you will find outlines of lectures from past weeks. 

## Week 1
"You may not know it, but machine learning is all around you. When you type a query into a search engine, it’s how the engine fgures out which results to show you (and which ads, as well). When you read your e-mail, you don’t see most of the spam, because machine learning fltered it out. Go to Amazon.com to buy a book or Netfix to watch a video, and a machine-learning system helpfully recommends some you might like. Facebook uses machine learning to decide which updates to show you, and Twitter does the same for tweets. Whenever you use a computer, chances are machine learning is involved somewhere." - Excerpt from [Pedro Domingo](https://homes.cs.washington.edu/~pedrod/)'s [The Master Algorithm](https://www.amazon.com/Master-Algorithm-Ultimate-Learning-Machine/dp/0465065708)

Machine Learning is "A field of study that gives computers the ability to learn without being explicitly
programmed." - [Arthur Samuel](http://infolab.stanford.edu/pub/voy/museum/samuel.html) (1959)

More formally, "A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E." - [Tom Mitchell](www.cs.cmu.edu/~tom/) (1999)

**The essence of Machine Learning:**

* A pattern exists
* We cannot pin it down mathematically
* But we do have data on it

**The learning process:**

1. You feed the data to a learning algorithm
2. The learning algorithm spits out a hypothesis
3. You give the hypothesis a fresh input and it should ideally give you a reasonable output

**Types of Machine Learning:**

1. Supervised learning
    * Regression (e.g. stock market prediction)
    * Classification (e.g. spam filtering)
2. Unsupervised learning
    * Clustering (e.g. news aggregation)
4. Reinforcement learning
    * Automonous agents (e.g. Boston Dynamics' BIGDOG)

A simple approach is to simply return the label of the the instance in the data that is closest to the input. This is called the k-nearest neighbours algorithm, where k is a variable, usually an odd number, that dictates how many neighbours will be used to compute an output. There are two disadvantages to this approach: one, you need to carry that data along with yourself everywhere you go, and two, your predictions fail at inputs that are far away from your instances in your dataset.

A better approach is to learn a function that can map an input to an output. The simplest such algorithm is linear regression.

## Week 2
Please read upto and including Part I Linear Regression from [Lecture 1](http://cs229.stanford.edu/notes/cs229-notes1.pdf) of Stanford's [CS229 Machine Learning](http://cs229.stanford.edu/) course taught by Prof. Andrew Ng.
