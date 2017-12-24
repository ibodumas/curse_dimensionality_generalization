# curse_dimensionality_generalization

Curse of dimensionality refers to the effect of increased dimension. As the dimensionality (features) increases, the needed amount of data for a generalized model grows exponentially. In other words, as you add more features to an input space, you will need more data to accurately build a good model. As the feature increases the needed data grows exponentially.

The effect of the curse of dimensionality can be reduced by reducing the number of features, this concept is called feature extraction. A typical example of feature extraction is PCA (Principal Component Analysis), it finds a subspace of lower dimension such that the features that have low explained variance on the data are eliminated.

<u>Why do we talk about generalization with regard to learning problems?</u><br>
Generalization in learning is contrasting notion of discrimination learning. Generalization learning can be seen as learning general concept from a specific example, and how well the general concept performs on new data (from the problem domain) that the model has not seen. Hence, generalization is important in order to avoid overfitting and overfitting. Generalization helps to achieve a tradeoff between overfitting and underfitting.

<u>What is overfitting in learning?</u><br>
Overfitting can be regarded as having low bias and high variance. This can occur when a model fails to efficiently generalize from the training dataset. Overfitting can also be viewed as when a model greatly performs on seen data while it poorly performs on unseen data.
