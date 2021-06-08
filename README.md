# Ethic-SRS
# Code 
This is the code for a submitted paper on ethical session-based Recommendation using GNN.
We have implemented our methods in Pytorch.

Here are three datasets we used in our work:

1- Reddit https://www.kaggle.com/colemaclean/subreddit-interactions

2- Xing http://2016.recsyschallenge.com/

These two data are available from A-PGNN study: https://github.com/CRIPAC-DIG/A-PGNN

3- Diginetica: http://cikm2016.cs.iupui.edu/cikm-cup or https://competitions.codalab.org/competitions/11161

# Usage
First, run the file preprocess.py to preprocess the data.

For example:

```python preprocess.py --dataset=Xing```

Then, run the file main.py to train the model.

For example: 

```python main.py --dataset=Xing```

You can change the parameters according to the usage.

# Requirements
Python 3

PyTorch 0.4.0

# Some other GitHub links that this study is inspired by:
SR-GNN ("paper title: Session-Based Recommendation with Graph Neural Networks"): https://github.com/CRIPAC-DIG/SR-GNN

NISER ("paper title: NISER: Normalized Item and Session Representations with Graph Neural Networks"): https://github.com/johnny12150/NISER
