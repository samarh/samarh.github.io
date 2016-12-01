---
layout: single
author_profile: false
permalink: /dm/
---

Welcome to the webpage for the Fall 2016 Data Mining course. Below you will find outlines of lectures from past weeks with links to relevant material.

## Week 1
"You may not know it, but machine learning is all around you. When you type a query into a search engine, it’s how the engine figures out which results to show you (and which ads, as well). When you read your e-mail, you don’t see most of the spam, because machine learning fltered it out. Go to Amazon.com to buy a book or Netfix to watch a video, and a machine-learning system helpfully recommends some you might like. Facebook uses machine learning to decide which updates to show you, and Twitter does the same for tweets. Whenever you use a computer, chances are machine learning is involved somewhere." - Excerpt from [Pedro Domingo](https://homes.cs.washington.edu/~pedrod/)'s [The Master Algorithm](https://www.amazon.com/Master-Algorithm-Ultimate-Learning-Machine/dp/0465065708)

Machine Learning is "A field of study that gives computers the ability to learn without being explicitly
programmed." - [Arthur Samuel](http://infolab.stanford.edu/pub/voy/museum/samuel.html) (1959)

More formally, "A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E." - [Tom Mitchell](http://www.cs.cmu.edu/~tom/) (1999)

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
    * Automonous agents (e.g. Boston Dynamics' BigDog)

A simple approach is to simply return the label of the the instance in the data that is closest to the input. This is called the [k-nearest neighbours](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) algorithm, where k is a variable, usually an odd number, that dictates how many neighbours will be used to compute an output. There are two disadvantages to this approach: one, you need to carry that data along with yourself everywhere you go, and two, your predictions fail at inputs that are far away from your instances in your dataset.

A better approach is to learn a function that can map an input to an output.

**Talks**

* [Fei-Fei Li: How we're teaching computers to understand pictures](https://www.ted.com/talks/fei_fei_li_how_we_re_teaching_computers_to_understand_pictures?language=en), TED2015
* [Jeremy Howard: The wonderful and terrifying implications of computers that can learn](https://www.ted.com/talks/jeremy_howard_the_wonderful_and_terrifying_implications_of_computers_that_can_learn?language=en), TEDxBrussels 2014

## Week 2
Please read upto and including the LMS Algorithm under Part I Linear Regression from [Lecture 1](http://cs229.stanford.edu/notes/cs229-notes1.pdf) of Stanford's [CS229 Machine Learning](http://cs229.stanford.edu/) course taught by Prof. [Andrew Ng](http://www.andrewng.org/).

## Week 3
Data Mining is the "Extraction of interesting (non-trivial, implicit, previously unknown and potentially useful) patterns or knowledge from a huge amount of data." - [Jiawei Han](http://hanj.cs.illinois.edu/) (2011)

Cross Industry Standard Process for Data Mining, commonly known by its acronym [CRISP-DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining), is a data mining process model that describes commonly used approaches that data mining experts use to tackle problems.

**Statistical Analysis**

* [Lionel Messi is Impossible](https://fivethirtyeight.com/features/lionel-messi-is-impossible/)
* [Opta Joe](https://twitter.com/OptaJoe)

**Datasets**

* [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/)
* [Kaggle](https://www.kaggle.com/datasets)
* [KDnuggets](http://www.kdnuggets.com/datasets/index.html)
* [BigML](http://blog.bigml.com/list-of-public-data-sources-fit-for-machine-learning/)

**Tools**

* [Weka](http://www.cs.waikato.ac.nz/ml/weka/)
* [RapidMiner](https://rapidminer.com/)
* [Python](https://www.python.org/) + [SciKit-Learn](http://www.scikit-learn.org/)
* [R](https://www.r-project.org/)

**Course Project**

Please head over to [this](https://docs.google.com/forms/d/e/1FAIpQLSeLyZeD35IL9hMAEBJVYQvfgbMPmn6_sakWmafYrHbMA_cmaA/viewform) link to submit your project proposal. The submission deadline is 11:59 PM on Wednesday, the 5th of October, 2016.

Those of you who plan to do your project in Weka will first need to convert your dataset into a format it accepts. You can read about Weka's file format [here](http://www.cs.waikato.ac.nz/ml/weka/arff.html) and use [this](http://ikuz.eu/csv2arff/) handy tool to convert CSV files into the required ARFF ones.

## Week 4
Students who did not submit their project proposals by the submission deadline can now do so [here](https://docs.google.com/forms/d/e/1FAIpQLSeLyZeD35IL9hMAEBJVYQvfgbMPmn6_sakWmafYrHbMA_cmaA/viewform), subject to a 10-mark penalty. The hard deadline is 11:59 PM on Wednesday, the 12th of October, 2016. Any students who still fail to submit their proposals by then will lose all credit for the course project.

Students who have already submitted their proposals should start working on their projects by first looking into their chosen datasets in detail and figuring out what predictions can be made from the available attributes. You can even combine additional datasets in order to make more interesting predictions.

Here are links to a few useful resources to help you get started.

* [What is Data Mining?](http://www.anderson.ucla.edu/faculty/jason.frand/teacher/technologies/palace/datamining.htm)
* [The Scientific Data Mining Process](http://www.siam.org/books/ot112/ot112_chapter4.pdf)
* [An Overview of Data Mining Techniques](http://www.thearling.com/text/dmtechniques/dmtechniques.htm)

Additionally, you might also want to start learning how to carry out data mining experiments in your platform of choice. Below are links to video tutorials for Weka and RapidMiner, the simpler of the four tools listed above.

* [Weka Tutorial](https://www.youtube.com/watch?v=gd5HwYYOz2U&index=28&list=PLJbE6j2EG1pZnBhOg3_Rb63WLCprtyJag)
* [RapidMiner Tutorial](https://www.youtube.com/watch?v=aOaFxNWTTMA&list=PLssWC2d9JhOZLbQNZ80uOxLypglgWqbJA)

Please complete Week 2's reading before the next class.

## Week 5
Please read the following sections from the resources linked:

* [Linear Regression with Multiple Variables](http://www.holehouse.org/mlclass/04_Linear_Regression_with_multiple_variables.html)
  * Features and polynomial regression
* [Regularization](http://www.holehouse.org/mlclass/07_Regularization.html)
  * The problem of overfitting
  * Regularized linear regression
* [Advice for Applying Machine Learning](http://www.holehouse.org/mlclass/10_Advice_for_applying_machine_learning.html)
  * Evaluating a hypothesis
  * Model selection and training/validation/test sets
  * Diagnosis - bias vs. variance
  * Regularization and bias/variance

Good luck for your midterms!

## Week 6
Please read the following sections from the resources linked:

* [Advice for Applying Machine Learning](http://www.holehouse.org/mlclass/10_Advice_for_applying_machine_learning.html)
  * Learning curves
* [Linear Regression with Multiple Variables](http://www.holehouse.org/mlclass/04_Linear_Regression_with_multiple_variables.html)
  * Gradient descent in practice: feature scaling
* [Anomaly Detection](http://www.holehouse.org/mlclass/15_Anomaly_Detection.html)
  * Problem motivation
  * Gaussian distribution
  * Anomaly detection algorithm

**Course Project**

Listed below are the sections that must be a part of your project report and presentation. The deadlines for the submission of both will be announced soon.

* Introduction
* Related Work
* Dataset
* Methods
* Experiments
* Results
* Discussion
* Conclusion
* References

You are *strongly* advised to go through [these](http://cs229.stanford.edu/projects2015.html) project reports from Stanford's [CS229 Machine Learning](http://cs229.stanford.edu/) course in order to get an idea of how you should write your own. All reports must be based on the [IEEE Manuscript Template](https://www.ieee.org/documents/trans_jour.docx). There is a zero tolerance policy towards plagiarism.

**IMPORTANT**

Dr. Shahbaz has reviewed your proposals and is of the opinion that the groups listed below might want to reconsider their chosen topics. They can look into other datasets and email me or meet with me after the next class if they wish to discuss anything.

* 2013-EE-04, 2013-EE-06, 2013-EE-52, 2013-EE-55
* 2013-CS-63, 2013-CS-68, 2013-CS-62
* 2013-EE-147, 2013-CS-29, 2013-CS-31, 2013-CS-32
* 2013-CS-18, 2013-CS-07, 2013-CS-16
* 2013-CS-19, 2013-CS-11, 2013-CS-30

## Week 7
Please read the following sections from the resources linked:

* [Clustering](http://www.holehouse.org/mlclass/13_Clustering.html)
  * All of it

**Course Project**

The deadline for the submission of the project report is 11:59 PM on Wednesday, the 14th of December, 2016. The project presentations will be held in the following class.

## Week 8
Please read the following sections from the resources linked:

* [Logistic Regression](http://www.holehouse.org/mlclass/06_Logistic_Regression.html)
  * All of it

## Week 9
Please go through the following documents and code from the repository linked:

* [ML Class Solutions](https://github.com/merwan/ml-class)
  * ex1.pdf
  * mlclass-ex1
  * ex2.pdf
  * mlclass-ex2
