
# Machine Learning: Regression


The first deep-dive into ML methods!

At this point, I implemented  my own machine learning algorithms for regression from scratch, addressing some hugely important models, such as ridge regression and lasso.

## What's inside?
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
          <td><ul><li>Linear regression</li><li>Regularization: Ridge (L2), Lasso (L1)</li><li>Nearest neighbor and kernel regression</li></ul></td>
        </tr>
        <tr>
          <td>Algorithms</td>
          <td><ul><li>Gradient descent</li><li>Coordinate descent</li></ul></td>
        </tr>
        <tr>
          <td>Concepts</td>
          <td><ul><li>Loss functions, bias-variance tradeoff</li><li>cross-validation, sparsity, overfitting</li><li>model selection, feature selection</li></ul></td>
        </tr>
      </table>
    </td>
    <td>
      <ul>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week1/programming%20assignment/Simple%20Linear%20Regression.ipynb">Fitting a simple linear regression model on housing data</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week2/programming%20assignment/Multiple%20Regression%20(Interpretation).ipynb">Exploring different multiple regression models for house price prediction</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week2/programming%20assignment/Multiple%20Regression%20(gradient%20descent).ipynb">Implementing gradient descent for multiple regression</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week3/programming%20assignment/Assessing%20Fit%20(polynomial%20regression).ipynb">Exploring the bias-variance tradeoff</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week4/programming%20assignment/Ridge%20Regression%20(interpretation).ipynb">Observing effects of L2 penalty in polynomial regression</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week4/programming%20assignment/Ridge%20Regression%20(gradient%20descent).ipynb">Implementing ridge regression via gradient descent</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week5/programming%20assignment/LASSO%20(Interpretation).ipynb">Using LASSO to select features</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week5/programming%20assignment/LASSO%20(coordinate%20descent).ipynb">Implementing LASSO using coordinate descent</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week6/programming%20assignment/K-Nearest%20Neighbors%20Regression.ipynb">Predicting house prices using k-nearest neighbors regression</a>
        </li>
      </ul>
    </td>
  </tr>
</table>

- Week 1: Simple Linear Regression:
    - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week1)
    - Describe the input (features) and output (real-valued predictions) of a regression model
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters to minimize RSS using gradient descent
    - Interpret estimated model parameters
    - Exploit the estimated model to form predictions
    - Discuss the possible influence of high leverage points
    - Describe intuitively how fitted line might change when assuming different goodness-of-fit metrics
    - [x] [Programming Assignment: Fitting a simple linear regression model on housing data](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week1/programming%20assignment/Simple%20Linear%20Regression.ipynb) 
    
- Week 2: Multiple Regression: Linear regression with multiple features
    - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week2)
    - Describe polynomial regression
    - Detrend a time series using trend and seasonal components
    - Write a regression model using multiple inputs or features thereof
    - Cast both polynomial regression and regression with multiple inputs as regression with multiple features
    - Calculate a goodness-of-fit metric (e.g., RSS)
    - Estimate model parameters of a general multiple regression model to minimize RSS:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Interpret the coefficients of a non-featurized multiple regression fit
    - Exploit the estimated model to form predictions
    - Explain applications of multiple regression beyond house price modeling
    - [x] [Programming Assignment: Exploring different multiple regression models for house price prediction](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week2/programming%20assignment/Multiple%20Regression%20(Interpretation).ipynb)
    - [x] [Programming Assignment: Implementing gradient descent for multiple regression](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week2/programming%20assignment/Multiple%20Regression%20(gradient%20descent).ipynb)
    
- Week 3: Assessing Performance
    - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week3)
    - Describe what a loss function is and give examples
    - Contrast training, generalization, and test error
    - Compute training and test error given a loss function
    - Discuss issue of assessing performance on training set
    - Describe tradeoffs in forming training/test splits
    - List and interpret the 3 sources of avg. prediction error
      - Irreducible error, bias, and variance
    - Discuss issue of selecting model complexity on test data and then using test error to assess generalization error
    - Motivate use of a validation set for selecting tuning parameters (e.g., model complexity)
    - Describe overall regression workflow
    - [x] [Programming Assignment: Exploring the bias-variance tradeoff](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week3/programming%20assignment/Assessing%20Fit%20(polynomial%20regression).ipynb)
    
- Week 4: Ridge Regression
    - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week4)
    - Describe what happens to magnitude of estimated coefficients when model is overfit
    - Motivate form of ridge regression cost function
    - Describe what happens to estimated coefficients of ridge regression as tuning parameter λ is varied
    - Interpret coefficient path plot
    - Estimate ridge regression parameters:
      - In closed form
      - Using an iterative gradient descent algorithm
    - Implement K-fold cross validation to select the ridge regression tuning parameter λ
    - [x] [Programming Assignment: Observing effects of L2 penalty in polynomial regression](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week4/programming%20assignment/Ridge%20Regression%20(interpretation).ipynb)
    - [x] [Programming Assignment: Implementing ridge regression via gradient descent](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week4/programming%20assignment/Ridge%20Regression%20(gradient%20descent).ipynb)
    
- Week 5: Lasso Regression: Regularization for feature selection
    - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week5)
    - Perform feature selection using “all subsets” and “forward stepwise” algorithms
    - Analyze computational costs of these algorithms
    - Contrast greedy and optimal algorithms
    - Formulate lasso objective
    - Describe what happens to estimated lasso coefficients as tuning parameter λ is varied
    - Interpret lasso coefficient path plot
    - Contrast ridge and lasso regression
    - Describe geometrically why L1 penalty leads to sparsity
    - Estimate lasso regression parameters using an iterative coordinate descent algorithm
    - Implement K-fold cross validation to select lasso tuning parameter λ
    - [x] [Programming Assignment: Using LASSO to select features](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week5/programming%20assignment/LASSO%20(Interpretation).ipynb)
    - [x] [Programming Assignment: Implementing LASSO using coordinate descent](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week5/programming%20assignment/LASSO%20(coordinate%20descent).ipynb)
    
- Week 6: Going nonparametric: Nearest neighbor and kernel regression
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/2.Regression/week6)
  - Motivate the use of nearest neighbor (NN) regression
  - Define distance metrics in 1D and multiple dimensions
  - Perform NN and k-NN regression
  - Analyze computational costs of these algorithms
  - Discuss sensitivity of NN to lack of data, dimensionality, and noise
  - Perform weighted k-NN and define weights using a kernel
  - Define and implement kernel regression
  - Describe the effect of varying the kernel bandwidth λ or # of nearest neighbors k
  - Select λ or k using cross validation
  - Compare and contrast kernel regression with a global average fit
  - Define what makes an approach nonparametric and why NN and kernel regression are considered nonparametric methods
  - Analyze the limiting behavior of NN regression
  - Use NN for classification
  - [x] [Programming Assignment: Predicting house prices using k-nearest neighbors regression](https://github.com/aut-datahub/ML_Washington_University/blob/main/2.Regression/week6/programming%20assignment/K-Nearest%20Neighbors%20Regression.ipynb)

## Apendix
Course syllabus and more information are provided at [Machine Learning: Regression](https://www.coursera.org/learn/ml-regression)
