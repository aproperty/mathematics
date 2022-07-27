

Sigmoid
Related to Logistic Regression. For single-label/multi-label binary classification.

$$
\sigma(z) = \frac{1} {1 + e^{-z}}
$$






Cross Entropy
In binary classification, where the number of classes $M$ equals 2, Binary Cross-Entropy(BCE) can be calculated as:
$$-{(y\log(p) + (1 - y)\log(1 - p))}$$

If $M > 2$ (i.e. multiclass classification), we calculate a separate loss for each class label per observation and sum the result.
$$-\sum_{c=1}^M y_{o,c} \log(p_{o,c})$$


M - number of classes   
log - the natural log   
y - binary indicator (0 or 1) if class label c is the correct classification for observation o   
p - predicted probability observation o is of class c   