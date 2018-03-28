# Toxic Comment Classification: GRU Network with FastText Embeddings

### Overview
In this notebook, we'll be developing a model that can classify string comments based on their toxicity:
* `toxic`
* `severe_toxic`
* `obscene`
* `threat`
* `insult`
* `identity_hate`

This will be completed as part of the [Toxic Comment Classification](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) Kaggle competition. From the site:

>In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.

### Install
This notebook requires **Python 3**.  
Dependencies found in `requirements.txt`.

### Data
* `train.csv`, `test.csv`, and `sample_submission.csv` found [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data). Download to `/data`.
* FastText embeddings found [here](https://github.com/facebookresearch/fastText/blob/master/pretrained-vectors.md). Download to `/data`.

### Getting Started
Run `jupyter notebook toxic_comment_classification.ipynb`.
