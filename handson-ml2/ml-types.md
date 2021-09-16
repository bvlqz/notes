# Types

**Supervised**

Trained with human supervision, the data you feed includes the desired solutions
* k-Nearest neighbors
* Linear Regression
* Logistic Regression
* Support Vector Machines
* Decision Trees and Random Forest
* Neural Networks (in some cases)

**Unsupervised**

Trained without human supervision, the training data is unlabeled. The system tries to learn without a teacher.

* Clustering
    * K-Means
    * DBSCAN
    * Hierarchical Cluster Analysis
* Anomaly detection and novelty detection
    * Anomaly detection: train with mostly normal instances and when it sees a new one it can tell wether it looks like a normal one or an anomaly
    * Novelty detection: Detect new instances that look different from all instances in the training set
    * One-class SVM
    * Isolation Forest
* Visualization and dimensionality reduction
    * Principal Component Analysis
    * Kernel PCA
    * Locally Linear Embedding 
    * t-Distributed Stochastic Neighbor Embedding (t-SNE)
    
Feature Extraction: Simplify the data without loosing too much information, one way to do it is to merge several correlated features into one, it is a good idea to try and reduce the dimension of the training data before feeding it to another ML algorithm

* Association rule learning

Dig large amounts of data and discover interesting relations between attributes

* Apriori
* Eclat

**Semisupervised**

For when you have plenty of unlabeled instances

* Deep belief networks
* Restricted Boltzmann Machines

**Reinforcement Learning**

The learning system is called an agent, an agent can get rewards or penalties and then learn by itself what is the best strategy (policy) to get the most reward over time. The policy defines what action the agent should choose.

**Batch Learning**

The system is not capable of learning incrementally, it must be trained. When it launches runs without learning anymore

**Online Learning**

Learn incrementally on the fly, feed the system to learn about new data on the fly.

**Instance-Based**

Compare new data points to known data points. 
It generalized to new instances by using a similarity measure to compare them to the learned distances.
Relies on a similarity measure to make predictions.

**Model-Based**

Detect patterns in the training data and build a predictive model. Tunes parameters to fit the model to the training set.
