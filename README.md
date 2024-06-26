# Machine Learning Study Log

## Date: June 8, 2024

### Overview
Today, I reviewed the fundamental concepts of Linear Regression.
### Topics Reviewed

#### 1. Linear Regression
- **Definition**: A linear approach to modeling the relationship between a dependent variable and one or more independent variables.
- **Steps**:
  - Define Linear Hypothesis function
  - Cost Function to that Hypothesis function
  - Use Gradient Descent to minimize the cost function and get the parameters.
  - Boom! We have trained our linear regression model. 

## Date: June 9, 2024

### Overview
Today, I reviewed the fundamental concepts of machine learning, including Logistic Regression and KNN.

#### 2. Logistic Regression
- **Definition**: A statistical method for predicting binary outcomes from a set of continuous or categorical predictor variables.
- **Key Points**:
  - Uses for classificaiton problems
  - The idea is basically finding the linear candidate line from the probability candidate line. 
  - First, project the data to linear candidate line, then using sigmoid funciton, convert it to proabilty candidate line.
  - Cost function is likelyhood. The goal is to find maximum likelyhood. 
  - Use gradient descent/ascent according to you equation. 

#### 3. KNN (K-Nearest Neighbour )
- **Definition**: A simple, learning algorithm that classifies a data point based on the majority class of its k-nearest neighbors.
- **Key Points**:
  - Non-parametric and lazy learning algorithm.
  - Calculate Euclidean Distance, Sort the distances, Find the K-neighbours
  - Take the hightest neighbour group to classify 

## Date: June 12, 2024

### Overview
Today, I reviewed the fundamental concepts of neural networks. 

#### 4. Neural Network

- **Definition**: A neural network is a squiggle line fitting machine that fits the activation functions with layers to the data
- **Key Points**:
  - Input Layers, Hidden Layers, Output Layers, each layer can have multiple nodes or neurons
  - Each Neuron is a activation functions, sigmoid, ReLU, softplus, etc..
  - Neurons are connected by connections, each connection consists of weights and bias.
  - Learning process is finding the best weights and bias to fit the data. 
  ***Back Propagation***
    - We have hypotheis ( prediction function )
    - We have cost function SSR
    - We use gradient descent with partial differentiation to related parameter starting from the back weights and bias of the network.


## Date: June 13, 2024

### Overview
Today, I reviewed the fundamental concepts of Decision Trees 

#### 5. Decision Trees ( Classification )

- **Definition**: A classification tree is a type of decision tree, where each branch represents yes or no decision. 
- **Key Points**:
  - Impurity of the node: The quality of the split for classification
  - Methods for calculating impurities of node: 1. Gini Impurity 2.Entropy
    **How to build**
    1. **Determine the Impurity of Nodes**
    2. **Select the root node with the lowest impurity**
    3. **Recursive Splitting: After selecting the root node, split the dataset into subsets based on the chosen feature**
    4. **Continue splitting** until stopping criteria are met


