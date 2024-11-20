# ABSA-BiLSTM

This project contains PyTorch implementaions for the report [Exploring Aspect-Based Sentiment Analysis through Bi-LSTM Networks with Novel Attention Mechanisms](/ABSA-BiLSTM.pdf).

![LICENSE](https://img.shields.io/packagist/l/doctrine/orm.svg)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

## Overview

The project involves a comparative study of three BiLSTM architectures with novel attention mechanisms for Multi-Aspect Multi-Sentiment classification based tasks. MAMS is a challenge dataset for aspect-based sentiment analysis (ABSA), in which each sentences contain at least two aspects with different sentiment polarities.
The three networks explored are:

- Concatenating Sentence and Aspect in Input Layer
- Separate Sentence and Aspect with Cross Attention
- Separate Bi-LSTM and Bidirectional Cross Attention on Sentence and Aspect

## Data

"A Challenge Dataset and Effective Models for Aspect-Based Sentiment Analysis", Qingnan Jiang, Lei Chen, Ruifeng Xu, Xiang Ao, Min Yang. (EMNLP-IJCNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-1654.pdf) [[data]](https://github.com/siat-nlp/MAMS-for-ABSA)

## Usage

A detailed Jupyter Notebook is provided for data exploration, preprocessing, model building, and evaluation.

## Contributors

- Alexander Turner
- Trieu Huynh
- Amy Wing Tung Hung

## Licence

MIT
