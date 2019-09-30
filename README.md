---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 5 Sec 33 V2         <br/>
**Topic**: KNN <br/>
**Amount of time**: 60 minutes <br/>
**Author**: Alison Peebles


***

#### Lesson Summary:

This lesson begins with an interactive activity in which students list people of varying degrees of relations. This is then used as an active demonstration of how a recommendation system (such as the netflix recommendation system) can be constructed based on a distance metric such as individual's strenght of relationship to one another. After strengthening student's intuition regarding KNN, the algorithm is then formally reviewed, including a discussion of multiclass problems, varying values of K and a review of euclidean distance. From there, implementing KNN via scikit-learn is reviewed. The lesson then concludes with discussing finding optimal values of K and how this parameter influences the bias and variance of subsequent results.

#### Topic:

KNN

#### Learning goals for this lesson:

* Students will be able to explain how KNN can be used to generate recommendations.
* Students will be able to implement KNN using scikit-learn.


#### Prerequisite knowledge:

* Students should be familiar with pandas DataFrames.
* Students should be familiar with train-test-split 

#### Prequisite Learn-Materials:

[K-Nearest Neighbors](https://github.com/learn-co-curriculum/dsc-k-nearest-neighbors)
[Distance Metrics](https://github.com/learn-co-curriculum/dsc-distance-metrics)
[KNN with scikit-learn](https://github.com/learn-co-curriculum/dsc-knn-with-scikit-learn)

#### Post Learn-Materials:

[Distance Metrics Learn](https://github.com/learn-co-curriculum/dsc-distance-metrics-lab)
[K-Nearest Neighbors Lab](https://github.com/learn-co-curriculum/dsc-k-nearest-neighbors-lab)
[Finding the Best Value for K](https://github.com/learn-co-curriculum/dsc-finding-the-best-value-for-k)
[KNN with scikit-learn Lab](https://github.com/learn-co-curriculum/dsc-knn-with-scikit-learn-lab)


#### Relevant learning goals from Airtable: 

KNN.1.rec4dxpfolXOHtZp0
KNN.1.recTnMxjiDvjwwzX2
KNN.1.recSeO6vuI8DSCuEw
KNN.1.recnqrsvdtjcxjsiU


KNN.2.recZCVw68dbSI2uV6
KNN.2.recRCgWQBrwhpZ0kR
KNN.2.recZCVw68dbSI2uV6
KNN.2.recZXfaM3MsYmpwv8
KNN.2.recRCgWQBrwhpZ0kR
KNN.2.recdPx1s5rxm7oahP
KNN.2.recqn7hrDmn6ndaZf
KNN.2.recdPx1s5rxm7oahP

KNN.3.rechxeOVt4YdDLilA

KNN.4.recnyF0QpiswLepR9

#### Materials

* Ipython notebook
* Activity Worksheet (pdf; print out copies for students)
* Slides

#### Vocab / Concepts 

* Euclidean distance
* KNN - K-Nearest Neighbors 

#### Lesson Outline:

* The Netlifx Challenge and Relationship Mapping
	> Teacher Introduction: Today, we'll take a look at the K-Nearest Neighbors algorithm. It is a straightforward and highly adaptable algorithm in which you select the closest relative data points and generate predictions from these points. One application of this is recommendation systems. For example, if you wanted to produce movie recommendations for someone, its reasonable to recommend movies that people with similar movie tastes also enjoy. The KNN algorithm would compare individuals movie recommendations to establish a distance metric of how similar people's movie tastes were to one another. From there, you would select an number K, of neighbors that are then used as the pool generate recommendations. For example, you might set K=10, in which case you would use the 10 most similar user's ratings to generate recommendations. Determining an optimal number of neighbors K is something we'll explore later in class.

	> Time for students to brainstorm

* KNN Algorithm Procedure
	* Start by examining the points pictured and posing the question of what class it should be classified as. Then, explain how this would be determined using the KNN algorithm. 
	* Raise Nuances / exceptions:
		* Discuss how to handle ties for the nth neighbor.
		* Discuss Weighting
		* Discuss cartesian distance
* KNN with scikit-learn
	* Review general procedural outline
	* Examine each step
* Discuss different values of k
	* 'Elbow' method
	* Bias vs Varianc with varying values of k
* Summary