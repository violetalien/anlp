# ANLP Project Repository

This repository contains several rudimentary notebooks
exploring the Text Summarization task - from the extractive,
as well as the abstractive point of view.

# prerequisites

Download the wikihowAll.csv from https://github.com/mahnazkoupaee/WikiHow-Dataset

# data

This directory contains a news article from The Guardian
for manual evaluation

# notebooks

This directory contains notebooks for different scenarios and algorithms used

Every notebook should be good on its own, meaning that apart from
changing the directory paths, every notebook is self-containable
and can be run from scratch

1. huggingface_wikihow_summarization - makes use of the summarization pipeline of huggingface, which is then used from scratch

2. LSTM-with-attention-wikihow.ipynb - uses a LSTM Encoder/Decoder Model with Decoder Attention  
to train on short articles and summaries

3. extractive-summarization-simple.ipynb - implement a simple word frequency based extractive method for text summarization and evaluates

4. extractive-summarization-page-rank.ipynb - implements an extractive method  based on the page rank algorithm


# Disclaimer

All the references and results are to be listed in the 
project report
