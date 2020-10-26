# Evaluation Metrics in Classification

## Classification accuracy

### Example

![](../.gitbook/assets/image%20%2882%29.png)

### Accuracy

Distance of the value in the test set and the value of the predicted labels.

## Jaccard index

![](../.gitbook/assets/image%20%2845%29.png)

## F1-score

 T: True

P: positive

F: False

N: Negetive

Calculate the precision and recall each label.



**Precision** 

* Precision = TP/\(TP+FP\)
* Recall = TP/\(TP+FN\)
* F1-score = 2\*\(prc\*rec\)/\(prec+rec\)

![](../.gitbook/assets/image%20%2893%29.png)

![](../.gitbook/assets/image%20%281%29.png)

![](../.gitbook/assets/image%20%2839%29.png)

{% hint style="info" %}
Both Jaccard and F1-score can be used for multi-class classifiers.
{% endhint %}

## Log loss

Sometimes the output of a classifier is the probability of a class label value between 0 and 1.

![](../.gitbook/assets/image%20%2841%29.png)

