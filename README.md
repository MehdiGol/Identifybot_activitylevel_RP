# Replication package for identify bot comments

This repository contains the replication package for our study about identifying bots at the level of their activity in GitHub submitted to BotSE'21 conference (*"Identifying bot activity in GitHub pull request and issue comments"*). 
A link to the paper will be added to this README as soon as the paper is accepted.

## Ground-truth dataset
The dataset is extracted from the ground-truth dataset of our study about [identifying bots](https://arxiv.org/abs/2010.03303) published in JSS journal.

## Replication package

A- Dataset preparation.ipynb: This notebook splits the dataset to two disjoint set for training and test purposes. To avoid any conflict with GDPR regulations we've anonymised the account name columns.

B- Model construction.ipynb: We followed a Grid-search cross validation in this notebook to find the best classifier and construct the final mode. The replication package was originally created on Python 3.8  and the dependencies required to run these notebooks are listed in requirements.txt and can be automatically installed using pip install -r requirements.txt.

C- Model evaluation.ipynb: this notebook contains scripts to evaluate the classifier.

