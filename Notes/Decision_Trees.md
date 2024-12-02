## Decision Trees

- SUPERVISED machine learning algorithm

- Works for Classification and Regression
  - Regression $\rightarrow$ Use MSE as impurity metric
  - Regression $\rightarrow$ Output = piecewise function

- Use Impurity to train

- Popular Impurity metric: GINI INDEX 

- Stopping Criteria $\rightarrow$ prevent Overfitting 
  -  Max Depth: Limit height of tree
  -  Min Sample: Specify minimum number of sample required to split 
    
## Random Forest
- Bagging Algorithm
- Improves Decsion Tree $\rightarrow$ Powerfull regularization effect
- Reduce Sensitivity to individual data points (ouliers)

### Technique 
- Use multiple Decision Trees with different sets of data (can include dupes)
  - Reggression: Average
  - Classification: Majority voting
  

