# Machine Learning Study Log

## Date: June 8, 2024

### Overview
Today, I reviewed the fundamental concepts of machine learning, including Linear Regression.
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
Today, I reviewed the fundamental concepts of machine learning, including Logistic Regression.

#### 2. Logistic Regression
- **Definition**: A statistical method for predicting binary outcomes from a set of continuous or categorical predictor variables.
- **Key Points**:
  - Uses for classificaiton problems
  - The idea is basically finding the linear candidate line from the probability candidate line. 
  - First, project the data to linear candidate line, then using sigmoid funciton, convert it to proabilty candidate line.
  - Cost function is likelyhood. The goal is to find maximum likelyhood. 
  - Use gradient descent/ascent according to you equation. 

#### 3. Decision Trees
- **Definition**: A non-linear predictive model that maps observations about an item to conclusions about the item's target value.
- **Key Points**:
  - Comprised of nodes representing decisions or conditions, with branches denoting the outcomes of these decisions.
  - Easy to interpret and visualize.
  - Prone to overfitting but can be mitigated using techniques like pruning.

#### 4. Gradient Boosting
- **Definition**: An ensemble technique that combines the predictions of several base estimators to improve robustness and accuracy.
- **Key Points**:
  - Builds models sequentially, with each new model attempting to correct the errors of the previous ones.
  - Commonly used variants include Gradient Boosting Machines (GBM), XGBoost, and LightGBM.
  - Effective in handling various types of data and achieving high predictive performance.

#### 5. Neural Networks
- **Definition**: Computational models inspired by the human brain, consisting of interconnected groups of artificial neurons that process information using a connectionist approach.
- **Key Points**:
  - Consists of input, hidden, and output layers.
  - Can model complex non-linear relationships.
  - Trained using backpropagation and gradient descent methods.
  - Popular architectures include Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs).

#### 6. K-Nearest Neighbors (KNN)
- **Definition**: A simple, instance-based learning algorithm that classifies a data point based on the majority class of its k-nearest neighbors.
- **Key Points**:
  - Non-parametric and lazy learning algorithm.
  - The value of k determines the number of neighbors to consider and can significantly impact the performance of the model.
  - Commonly used for both classification and regression tasks.
  - Distance metrics such as Euclidean distance are used to find the nearest neighbors.
