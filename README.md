# Facebook-Friend-Recommenation-Graph-Mining

The project involves using data from the [FacebookRecruiting](https://www.kaggle.com/c/FacebookRecruiting/overview/description) challenge on [Kaggle](https://www.kaggle.com) to predict missing links from a given directed social graph to recommend users.
This is a supervised machine learning problem.

## Table of contents
* [General info](#general-info)
* [Setup](#setup)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

Taken data from facebook's recruting challenge on kaggle https://www.kaggle.com/c/FacebookRecruiting
data contains two columns source and destination eac edge in graph - Data columns (total 2 columns):
- source_node int64
- destination_node int64

Generated training samples of good and bad links from given directed graph and for each link got some features like no of followers, is he followed back, page rank, katz score, adar index, some svd fetures of adj matrix, some weight features etc. and trained ml model based on these features to predict link.
Some reference papers and videos :
https://www.cs.cornell.edu/home/kleinber/link-pred.pdf
https://www3.nd.edu/~dial/publications/lichtenwalter2010new.pdf
https://kaggle2.blob.core.windows.net/forum-message-attachments/2594/supervised_link_prediction.pdf
https://www.youtube.com/watch?v=2M77Hgy17cg

## Setup

* Download all the Jupyter Notebooks at the same location on your computer.
* Download dataset(train and test data) and other data [here](https://drive.google.com/drive/folders/1pEBmIl1tbuwYrsfeUv2KDz8a2gR0Fjxe?usp=sharing).

### Install the requirements
 
* Install the requirements using `pip install -r requirements.txt`.
    * Make sure you use Python 3.
    
* Run the jupyter notebooks in the following order -
 1. FB_EDA.ipynb
 2. FB_featurization.ipynb
 3. FB_Models.ipynb
 

## Status
Project status: **Finished**

## Inspiration
This topic was a great opportunity to explore Facebook recruiting requirements and exploration of graph mining till its application.
## Contact
Feel free to contact me, send a mail to **pranshu1921@gmail.com**
