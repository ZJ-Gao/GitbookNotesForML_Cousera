---
description: >-
  1.  Train and test on the same dataset 2. Train/Test split 3. Regression
  evaluation metrics
---

# Model evaluation approaches

## Best approach for most accurate results

{% hint style="info" %}
The similarity of the predicted and actual values
{% endhint %}

### Training accuracy

* High training accuracy isn't necessary a good thing
* Result o over-fitting
  * Over-fit: the model is overly trained to the dataset, which may capture noise and produce a non-generalized model.

### Out-of-Sample Accuracy

* It's important that our models have high, out-of-sample accuracy, because we want our model to predict unknown things.
* How can we improve out-of-sample accuracy?
  * Train/test split 

### Train/test split

Train with the training set and test with the test set

![](../.gitbook/assets/image%20%2852%29.png)

#### K-fold cross-validation

The same dataset but each split is different.

The result is average to produce a more consistent out-of-sample accuracy.

![](../.gitbook/assets/image%20%2873%29.png)

![](../.gitbook/assets/image%20%28122%29.png)





