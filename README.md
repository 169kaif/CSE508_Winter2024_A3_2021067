# CSE508_Winter2024_A3_2021067
Solutions for Assignment 3 of CSE508

This assignment involved doing an analysis of the Electronics subset of the Amazon Reviews Dataset, which can be downloaded from the given link ```https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/#subsets```

Since, the data is large in nature, you might need to use chunking in order to pre-process this. I have pre-processed the data in the ```pre.ipynb``` file and generated pickle files for a further subset of headphones specifically.

In the ```main.ipynb```, I perform EDA on the imported headphones review and metadata data frame. 
It also involves building a 5-fold cross-validated recommender system using Collaborative Filtering.

```Word2Vec``` embeddings have been used in the ```main.ipynb``` file which has been pretrained on the ```GoogleNews-300M``` corpus.

In order to run the scripts:

<ol>
  <li>Download and import the necessary libraries.</li>
  <li>Downlaod the data and Word2Vec pre-trained embeddings.</li>
  <li>Run pre.ipynb to pre-process the dataset and obtain the picked headphones dataset.</li>
  <li>Run main.ipynb cell by cell to observe the EDA and to perform collaborative filtering.</li>
</ol>
