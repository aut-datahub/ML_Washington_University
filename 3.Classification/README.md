
# Machine Learning: Classification


The third course of this specialization is about Classification

Through this course, you will become familiar with the fundamental models and algorithms used in classification, as well as a number of core machine learning concepts.

## What's inside
<table>
  <tr>
    <th>Description</th>
    <th>Programming Assignments</th>
  </tr>
  <tr>
    <td>
      <table>
        <tr>
          <td>Models</td>
          <td><ul><li>Linear classifiers</li><li>Logistic regression</li><li>Decision trees</li><li>Ensembles</li></ul></td>
        </tr>
        <tr>
          <td>Algorithms</td>
          <td><ul><li>Stochastic gradient descent</li><li>Recursive greedy</li><li>Boosting</li></ul></td>
        </tr>
        <tr>
          <td>Concepts</td>
          <td><ul><li>Decision boundaries, MLE</li><li>ensemble methods, online learning</li></ul></td>
        </tr>
        <tr>
          <td>Core ML</td>
          <td><ul><li>Alleviating overfitting</li><li>Handling missing data</li><li>Precision-recall</li><li>Online learning</li></ul></td>
        </tr>
      </table>
    </td>
    <td>
      <ul>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week1/programming%20assignment/Logistic%20Regression%20Exploration.ipynb">Predicting sentiment from product reviews</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week2/programming%20assignment/Logistic%20Regression%20Implementation.ipynb">Implementing logistic regression from scratch</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week2/programming%20assignment/Logistic%20Regression%20Regularization.ipynb">Implementing Logistic Regression with L2 regularization</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week3/programming%20assignment/Decision_Trees_Exploration.ipynb">Identifying safe loans with decision trees</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week3/programming%20assignment/Decision_Trees_Implementation.ipynb">Implementing binary decision trees from scratch</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week4/programming%20assignment/Decision_Trees_Overfitting.ipynb">Decision Trees in Practice for preventing overfitting</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week5/programming%20assignment/Boosting_Exploration.ipynb">Exploring Ensemble Methods with pre-implemented gradient boosted trees</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week5/programming%20assignment/AdaBoost_Implementation.ipynb">Implement your own boosting module(AdaBoost)</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week6/programming%20assignment/Precision_Recall.ipynb">Exploring precision and recall</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week7/programming%20assignment/Stochastic_Gradient.ipynb">Training Logistic Regression via Stochastic Gradient Ascent</a>
        </li>
      </ul>
    </td>
  </tr>
</table>

- Week 1: 
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week1)
  - Linear Classifiers & Logistic Regression
  - decision boundaries
  - linear classifiers
  - class probability
  - logistic regression
  - impact of coefficient values on logistic regression output
  - 1-hot encoding
  - multiclass classification using the 1-versus-all
  - [x] [Programming Assignment: Predicting sentiment from product reviews](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week1/programming%20assignment/Logistic%20Regression%20Exploration.ipynb)
- Week 2: 
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week2)
  - Learning Linear Classifiers
    - Maximum likelihood estimation
    - Gradient ascent algorithm for learning logistic regression classifier
    - Choosing step size for gradient ascent/descent
    - Deriving gradient of logistic regression
    - [x] [Programming Assignment: Implementing logistic regression from scratch](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week2/programming%20assignment/Logistic%20Regression%20Implementation.ipynb)  
  - Overfitting & Regularization in Logistic Regression
    - Overfitting in classification
    - Overconfident predictions due to overfitting
    - L2 regularized logistic regression
    - Sparse logistic regression
    - [x] [Programming Assignment: Implementing Logistic Regression with L2 regularization](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week2/programming%20assignment/Logistic%20Regression%20Regularization.ipynb)
- Week 3:
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week3)
  - Decision Trees
  - Predicting loan defaults with decision trees
  - Learning decision trees
       - Recursive greedy algorithm
       - Learning a decision stump
       - Selecting best feature to split on
       - When to stop recursing
  - Using the learned decision tree
       - Traverse a decision tree to make predictions: Majority class predictions, Probability predictions, Multiclass classification
  - Learning decision trees with continuous inputs
       - Threshold splits for continuous inputs
       - Picking the best threshold to split on
  - [x] [Programming Assignment: Identifying safe loans with decision trees](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week3/programming%20assignment/Decision_Trees_Exploration.ipynb)
  - [x] [Programming Assignment: Implementing binary decision trees from scratch](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week3/programming%20assignment/Decision_Trees_Implementation.ipynb)
- Week 4
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week4)
  - Overfitting in decision trees 
    - Identify when overfitting in decision trees
    - Prevent overfitting with early stopping
      - Limit tree depth
      - Do not consider splits that do not reduce classification error
      - Do not split intermediate nodes with only few points
    - Prevent overfitting by pruning complex trees
      - Use a total cost formula that balances classification error and tree complexity
      - Use total cost to merge potentially complex trees into simpler ones 
    - [x] [Programming Assignment: Decision Trees in Practice for preventing overfitting](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week4/programming%20assignment/Decision_Trees_Overfitting.ipynb) 
  - Handling missing data 
    - Describe common ways to handling missing data:
      1. Skip all rows with any missing values
      2. Skip features with many missing values
      3. Impute missing values using other data points
    - Modify learning algorithm (decision trees) to handle missing data:
      1. Missing values get added to one branch of split
      2. Use classification error to determine where missing values go 
- Week 5
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week5)
  - Boosting 
  - Identify notion ensemble classifiers
  - Formalize ensembles as the weighted combination of simpler classifiers
  - Outline the boosting framework – sequentially learn classifiers on weighted data
  - Describe the AdaBoost algorithm
    - Learn each classifier on weighted data
    - Compute coefficient of classifier
    - Recompute data weights
    - Normalize weights
  - Implement AdaBoost to create an ensemble of decision stumps
  - Discuss convergence properties of AdaBoost & how to pick the maximum number of iterations T 
  - [x] [Programming Assignment: Exploring Ensemble Methods with pre-implemented gradient boosted trees](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week5/programming%20assignment/Boosting_Exploration.ipynb)
  - [x] [Programming Assignment: Implement your own boosting module (Adaboost)](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week5/programming%20assignment/AdaBoost_Implementation.ipynb)
- Week 6 
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week6)
  - Evaluating classifiers: Precision & Recall 
  - Classification accuracy/error are not always right metrics
  - Precision captures fraction of positive predictions that are correct
  - Recall captures fraction of positive data correctly identified by the model
  - Trade-off precision & recall by setting probability thresholds
  - Plot precision-recall curves.
  - Compare models by computing precision at k
  - [x] [Exploring precision and recall](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week6/programming%20assignment/Precision_Recall.ipynb)
- Week 7
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/3.Classification/week7)
  - Scaling to Huge Datasets & Online Learning 
  - Significantly speedup learning algorithm using stochastic gradient
  - Describe intuition behind why stochastic gradient works
  - Apply stochastic gradient in practice
  - Describe online learning problems
  - Relate stochastic gradient to online learning 
  - [x] [Training Logistic Regression via Stochastic Gradient Ascent](https://github.com/aut-datahub/ML_Washington_University/blob/main/3.Classification/week7/programming%20assignment/Stochastic_Gradient.ipynb)

## Apendix
Course syllabus and more information are provided at [Machine Learning: Classification](https://www.coursera.org/learn/ml-classification)
