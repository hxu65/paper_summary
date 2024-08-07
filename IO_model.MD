# Dynamic Trees for Learning and Design
https://doi.org/10.48550/arXiv.0912.1586  <br>

  Dynamic Regression Trees: These trees adapt over time with new data, allowing for efficient on-line posterior filtering of tree states using particle learning algorithms. This results in better performance at a lower cost compared to traditional methods. <br/>
  here are three possible moves that can be applied to the tree's structure at each time step when new data is observed:<br>
  **Stay**: The tree structure remains unchanged,  If the tree stays the same, the new data point is simply incorporated without changing the tree structure. <br/>
  **Prune**: The tree is pruned by removing a node and its subtree. In pruning, a node and its sibling (if it exists) are removed, making their parent a new leaf node.  <br/>
**Grow**: The tree grows by adding a new partition based on a new split: Growing involves choosing a split dimension and split point to create two new leaf nodes from the existing node containing  <br/>


**Mechanism of Evolution**:<br>
Localized Changes: The tree evolution is localized to the region of the newly observed data point. <br>
This means that only the partition containing and its immediate neighborhood are considered for changes. <br>
Probabilities of Moves: Each of the possible moves (stay, prune, grow) is a priori equally probable, though this can be adjusted based on specific requirements. <br>


# Active Learning: Problem Settings and Recent Developments
https://10.48550/ARXIV.2012.04225 <br>
This paper introduces the basic problem setting and concept of active learning, including recent research trends and application examples.<br>
<ol>
  <li> terms and notations and explains the basic problem setting</li>
  <li> Typical criteria for selecting data that require labeling</li>
  <li> Results for theoretical guarantees of active learning</li>
  <li> Example of applying active learning to measurement and material development </li>
</ol>


# Active Learning Literature Survey
https://burrsettles.com/pub/settles.activelearning.pdf

### What is the key idea behind active learning?
machine learning algorithm can achieve greater accuracy with fewer training labels if it is allowed to choose the data from which it learns.



# esDNN: Deep Neural Network Based Multivariate Workload Prediction in Cloud Computing Environments

### Regression-Based Approaches for Cloud Workload Prediction
1. most of these approaches are only suitable for workloads with obvious patterns.

### Learning-Based Approaches for Cloud Workload Prediction
<ol>
 <li> most of the learning-based approaches are based on machine learning algorithms or traditional RNN, which either cannot exploit the long-term memory dependencies or address the gradient vanishing challenge. Thus, it is also difficult for them to predict cloud workloads accurately.
<li>  System model: 1. Data preprocessing: It include a workload preprcesssing component and a data cleaning component. Remove the empty data and label the data based on time. 
<li> Supervised Learning Conversion: It trains through the existing training samples to obtain an optimized model and then uses this model to map all inputs to the corresponding outputs. They use the supervised learning transfer function to convert the multivariate time series prediction problem into a supervised learning problem based on supervised learning algorithm.
<li>  EFFICIENT SUPERVISE LEARNING-BASED DEEP NEURAL NETWORK: A sliding window-based approach for multivariate time series prediction is applied to convert the original dataset into supervised learning-based time series data. 
<ol>

The algorithm used in this paper:
Sliding window for Multivariate Time series Forecasting (S-MTF) algorithm, which transforms a multivariate time series forecast into a supervised learning time series. The S-MTF algorithm can be applied to any time-related dataset, and it is still linearly related to time because it contains all the data of the previous moment at any time.


# Analysis and Modeling of the End-to-End I/O Performance on OLCF’s Titan Supercomputer

## Measurement Setup
<ol>
<li> Control which OST (the object storage target) the data will be written to  by leveraging the llapi provided by the Lustre file system
<li> The I/O measuring job needs to issue the I/O requests to the OSTs periodically and the time interval between two consecutive I/O requests should be short enough so that more I/O performance dynamics can be captured.
<li> Select the size of each I/O request as well as the OST each I/O request is sent to.


<ol>
## Key observation: The degree of busyness of each end-to-end I/O path in HPC systems can be characterized by three performance states: idle, transitional, and busy state.

## MODEL OF END-TO-END I/O PERFORMANCE
<ol>
<li> continuous-time hidden Markov model: the hidden variables (the three performance states in our case), which control the mixture component to be selected for each observation, follow a Markov process rather than independent of each other.
<li> Model Parameter Estimation: maximum likelihood estimation (MLE) 

<ol>




