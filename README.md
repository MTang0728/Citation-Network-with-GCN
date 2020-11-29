# Citation Network Analysis

## Intro:
This project uses the Cora citation network to examine the applicability of Graph Convolutional Network (GCN). The Cora dataset consists of 2708 scientific publications, where publications are interconnected through a citational relationship whose structure could be interpreted as a network. In this network, publications can be effectively encoded through Bag-of-Word and be represented by a feature matrix. And relationships can be translated into an adjacency matrix. GCN distinguishes itself from other machine learning classifiers by taking into account the intrinsic structural relationships between each node in the network. After comparing the model performance results of GCN with 3 traditional supervised classifiers, we find that GCN gains enhanced predictive power from the interconnectivity within the network. 

For a detailed analysis, please refer to the [report](./Resources/703_Team_Orange_Report.pdf)

## Other Classifiers Used:
- GCN (Graph Convolutional Network)
- Naive Bayes Classifier
- Logistic Regression Classifier
- KNeighbors Classifier

## Result:



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
- Shangwen Yan: [@Shangwen Yan](https://github.com/notfy111)
- Feng Yi: [@Feng Yi](https://github.com/shangwenyan)


