# Machine Learning: Clustering & Retrieval
The final course of this specialization is about Clustering and Retrieval.

Retrieval is used in almost every applications and device we interact with, like in providing a set of products related to one a shopper is currently considering, or a list of people you might want to connect with on a social media platform. Clustering can be used to aid retrieval, but is a more broadly useful tool for automatically discovering structure in data, like uncovering groups of similar patients.

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
          <td><ul><li>Nearest neighbors</li><li>Clustering, mixtures of Gaussians</li><li>Latent Dirichlet allocation (LDA)</li></ul></td>
        </tr>
        <tr>
          <td>Algorithms</td>
          <td><ul><li>K-means, MapReduce</li><li>K-NN, KD-trees, locality-sensitive hashing (LSH)</li><li>Expectation-maximization (EM)</li><li>Gibbs sampling</li></ul></td>
        </tr>
        <tr>
          <td>Concepts</td>
          <td><ul><li>Distance metrics, approximation algorithms,</li><li>hashing, sampling algorithms, scaling up with map-reduce</li></ul></td>
        </tr>
        <tr>
          <td>Core ML</td>
          <td><ul><li>Unsupervised learning</li><li>Probabilistic modeling</li><li>Data parallel problems</li><li>Bayesian inference</li></ul></td>
        </tr>
      </table>
    </td>
    <td>
      <ul>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week2/programming%20assignment/Nearest_Neighbors_Exploration.ipynb">Choosing features and metrics for nearest neighbor search</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week2/programming%20assignment/Locality_Sensitive_Hashing.ipynb">Implementing Locality Sensitive Hashing from scratch</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week3/programming%20assignment/K_Means_Clustering.ipynb">Clustering text data with k-means</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week4/programming%20assignment/Mixture_Models_EM.ipynb">Implementing EM for Gaussian mixtures</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week4/programming%20assignment/EM_in_High_Dim.ipynb">Clustering text data with Gaussian mixtures</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week5/programming%20assignment/Latent_Dirichlet_Allocation.ipynb">Modeling text topics with Latent Dirichlet Allocation</a>
        </li>
        <li>
          [x] <a href="https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week6/programming%20assignment/Hierarchical_Clustering.ipynb">Modeling text data with a hierarchy of clusters</a>
      </ul>
    </td>
  </tr>
</table>

Slides and more details about this course can be found in my Github [SSQ](https://github.com/SSQ/Coursera-UW-Machine-Learning-Clustering-Retrieval)

- Week 1 Intro
  - [Module's Lecture](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week1)

- Week 2 Nearest Neighbor Search: Retrieving Documents
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week2)
  - Implement nearest neighbor search for retrieval tasks
  - Contrast document representations (e.g., raw word counts, tf-idf,…)
    - Emphasize important words using tf-idf
  - Contrast methods for measuring similarity between two documents
    - Euclidean vs. weighted Euclidean
    - Cosine similarity vs. similarity via unnormalized inner product
  - Describe complexity of brute force search
  - Implement KD-trees for nearest neighbor search
  - Implement LSH for approximate nearest neighbor search
  - Compare pros and cons of KD-trees and LSH, and decide which is more appropriate for given dataset
  - [x] [Choosing features and metrics for nearest neighbor search](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week2/programming%20assignment/Nearest_Neighbors_Exploration.ipynb)
  - [x] [Implementing Locality Sensitive Hashing from scratch](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week2/programming%20assignment/Locality_Sensitive_Hashing.ipynb)

- Week 3 Clustering with k-means
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week3)
  - Describe potential applications of clustering
  - Describe the input (unlabeled observations) and output (labels) of a clustering algorithm
  - Determine whether a task is supervised or unsupervised
  - Cluster documents using k-means
  - Interpret k-means as a coordinate descent algorithm
  - Define data parallel problems
  - Explain Map and Reduce steps of MapReduce framework
  - Use existing MapReduce implementations to parallelize kmeans, understanding what’s being done under the hood
  - [x] [Clustering text data with k-means](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week3/programming%20assignment/K_Means_Clustering.ipynb)
  
- Week 4 Mixture Models: Model-Based Clustering
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week4)
  - Interpret a probabilistic model-based approach to clustering using mixture models
  - Describe model parameters
  - Motivate the utility of soft assignments and describe what they represent
  - Discuss issues related to how the number of parameters grow with the number of dimensions
    - Interpret diagonal covariance versions of mixtures of Gaussians
  - Compare and contrast mixtures of Gaussians and k-means
  - Implement an EM algorithm for inferring soft assignments and cluster parameters
    - Determine an initialization strategy
    - Implement a variant that helps avoid overfitting issues
  - [x] [Implementing EM for Gaussian mixtures](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week4/programming%20assignment/Mixture_Models_EM.ipynb)
  - [x] [Clustering text data with Gaussian mixtures](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week4/programming%20assignment/EM_in_High_Dim.ipynb)
    
- Week 5 Latent Dirichlet Allocation: Mixed Membership Modeling
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week5)
  - Compare and contrast clustering and mixed membership models
  - Describe a document clustering model for the bagof-words doc representation
  - Interpret the components of the LDA mixed membership model
  - Analyze a learned LDA model
    - Topics in the corpus
    - Topics per document
  - Describe Gibbs sampling steps at a high level
  - Utilize Gibbs sampling output to form predictions or estimate model parameters
  - Implement collapsed Gibbs sampling for LDA
  - [x] [Modeling text topics with Latent Dirichlet Allocation](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week5/programming%20assignment/Latent_Dirichlet_Allocation.ipynb)
  
- Week 6 Hierarchical Clustering & Closing Remarks
  - [Module's Lectures & Datasets](https://github.com/aut-datahub/ML_Washington_University/tree/main/4.Clustering%20%26%20Retrieval/week6)
  - Hierarchical clustering
    - Divisive clustering
    - Agglomerative clustering
      - The dendrogram for agglomerative clustering
      - Agglomerative clustering details
  - Hidden Markov models (HMMs): Another notion of “clustering”
  - [x] [Modeling text data with a hierarchy of clusters](https://github.com/aut-datahub/ML_Washington_University/blob/main/4.Clustering%20%26%20Retrieval/week6/programming%20assignment/Hierarchical_Clustering.ipynb)

## Apendix
Course syllabus and more information are provided at [Machine Learning: Clustering & Retrieval](https://www.coursera.org/learn/ml-clustering-and-retrieval)
