# Citation Network Analysis

## Intro:
This project uses the Cora citation network to examine the applicability of Graph Convolutional Network (GCN). The Cora dataset consists of 2708 scientific publications, where publications are interconnected through a citational relationship whose structure could be interpreted as a network. In this network, publications can be effectively encoded through Bag-of-Word and be represented by a feature matrix. And relationships can be translated into an adjacency matrix. This can be visualzied in the figure below:

<img src='https://github.com/MTang0728/Citation-Network-with-GCN/blob/master/Resources/cora.png?raw=true' width = '600' class="center">

GCN distinguishes itself from other machine learning classifiers by taking into account the intrinsic structural relationships between each node in the network. After comparing the model performance results of GCN with 3 traditional supervised classifiers, we find that GCN gains enhanced predictive power from the interconnectivity within the network. 

For a detailed analysis, please refer to the [report](./Resources/703_Team_Orange_Report.pdf).

## Other Classifiers Used:
- GCN (Graph Convolutional Network)
- Naive Bayes Classifier
- Logistic Regression Classifier
- KNeighbors Classifier

## Results:
Method | Result
------------ | -------------
Graph Convolutional Networks (GCN) | Mean accuracy on training set: 0.92 <br>Mean accuracy on testing set: 0.80
Naive Bayes Classifier (Multinomial) | Mean accuracy on training set: 0.99 <br>Mean accuracy on testing set: 0.58
Logistic Regression Classifier | Mean accuracy on training set: 1.00 <br>Mean accuracy on testing set: 0.59
K-Nearest Neighbors Classifier | Mean accuracy on training set: 1.00 <br>Mean accuracy on testing set: 0.33


## Package Used:
- **Pandas** for data manipulation
- **NumPy** for arithmetic operation
- **Spektral** for Citation Network dataset and GCN layer control
- **TensorFlow** for deep learning framework and running neural network models
- **scikit-learn** for running supervised classifiers and performance evaluation
- **matplotlib** for data visualization
- **NetworkX** for network visualization
- **seaborn** for data visualization

## Project Member:
- Jennie Sun: [@Jennie Sun](https://github.com/jenniesun)
- Michael Tang: [@Michael Tang](https://github.com/MTang0728)
- Shangwen Yan: [@Shangwen Yan](https://github.com/shangwenyan)
- Yi Feng: [@Yi Feng](https://github.com/notfy111)


