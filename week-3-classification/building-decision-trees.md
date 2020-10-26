# Building Decision Trees

### Practice example

Key point: which attribute is the best or more predictive to split data based on the feature.

If we choose cholestrerol

![](../.gitbook/assets/image%20%2887%29.png)

Judgement: bad attribute selection for split

if we choose sex

![](../.gitbook/assets/image%20%2880%29.png)

More **predictivenes**; less **impurity**, lower **entropy**

We're looking for the best feature to decrease the impurity of patients in the leaves

![](../.gitbook/assets/image%20%28114%29.png)

### Entropy

* Measure of randomness or uncertainty

![](../.gitbook/assets/image%20%28128%29.png)

> The lower the Entropy, the less uniform the distribution, the purer the node.

![](../.gitbook/assets/image%20%2835%29.png)

### Which attribute is the best?

![](../.gitbook/assets/image%20%2822%29.png)

The tree with the higher informatin gain after splitting.

Information gain is the information that can increase the level of certainty after splitting.

![](../.gitbook/assets/image%20%28106%29.png)





