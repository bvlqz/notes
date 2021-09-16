# Concepts

**Attribute or Feature**: Describes a data type

**Out-of-core learning**: Train systems on datasets that cannot fit in one machine main memory - load part of the data - run training step on that data - repeat until it has run on all data. 

**Learning rate**: how fast the system adapt to changing data, faster learning rate typically means the system will also forget the old data

**Generalization**: How many number of training examples are needed for the system to make good predictions on examples it has never seen before, in order for a model to generalize well, it is crucial that the training data be representative of the new cases that you want the model to generalize to.

**Utility function (fitness function)**: Measure hoy good the model is

**Cost function**: Measure how bad the model is

**Overfitting**: The model performs well on the training data, but it does not generalize well.

**Regularization**: Constraining a model to make it simpler and reduce the risk of overfitting.

**Hyperparamenter**: The amount of regularization to apply during learning (this is a parameter of the learning algorithm, not the model), it is set before training and remains constant during training

**Out-of-sample error**: Generalization error, tells how well the model will perform on instances it has never seen before. If training error is low, but generalization error is high, the model is over-lifting the training data 

**Validation Set**: Used to compare models, it makes it possible to select the best model and tune the hyperparamenters