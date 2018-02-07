# ctr-prediction
This repository contains interesting papers and projects in ctr prediction

## facebook

### Practical Lessons from Predicting Clicks on Ads at Facebook
gbdt + logistic regression

### Applied Machine Learning at Facebook: A Datacenter Infrastructure Perspective
infra in fb

## google

### Deep Neural Networks for YouTube Recommendations

It formulates the problem as a softmax classification, and uses dnn to train. The first layer is to concatenate the average embedding of video watch history and search history. The last layer is interesting: similar to word embedding, the last layer can be regarded as the user embedding, and the parameters of the matrix in the last layer can be regarded as all the embeddings of the video. 

In online prediction, it first computes the user embedding using feed-forward nn, and then apply a similar search over all the embedding vectors of videos.

