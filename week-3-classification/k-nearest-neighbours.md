# K-nearest Neighbours

## Intro to KNN



* objective : to build a classifier

![](../.gitbook/assets/image%20%2838%29.png)

* How to predicut Row 8?

Make a major vote in the red rectangle.

![](../.gitbook/assets/image%20%2829%29.png)

## Definition

A classification algorithm that takes a bunch of labeled points and uses them to learn how to label other points. The algorithnm classifies cases based on their similarity to ther cases.

Cases that are near each other are said to be '**neighbors**'

Based on **similar** cases with **same class labels** are **near** each other

**Distance** between two cases is a measure of their dissimilarity

## Work flow of the K-Nearest Neighbors algorithm

![](../.gitbook/assets/image%20%2872%29.png)

### How to calculate the distance/similarity?

#### One feature

![](../.gitbook/assets/image%20%2831%29.png)

#### More features

![](../.gitbook/assets/image%20%2842%29.png)

### How to find the best K value for KNN?

#### If K=1; choose a very low value of K

We are probably choose the noise in the data or an anomaly. Besides, this can also lead to a complex model and overfitting.

The model is probably not generalized enough to be used for out-of-sample cases. In other words, it can't be trusted enough to be used for prediction of unknown samples.

#### If we choose a very high value of K

The model can be overly generalized.

## Computing continuous targets using KNN

* KNN can be used for regression

