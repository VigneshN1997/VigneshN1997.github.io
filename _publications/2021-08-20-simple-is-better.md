---
title: "Simple is better: Making Decision Trees faster using random sampling"
collection: publications
date: 2021-08-20
venue: 'arxiv'
paperurl: 'https://arxiv.org/pdf/2108.08790.pdf'
---
In recent years, gradient boosted decision trees have become popular in building robust machine learning models on big data. The primary technique that has enabled these algorithms success has been distributing the computation while building the decision trees. A distributed decision tree building, in turn, has been enabled by building quantiles of the big datasets and choosing the candidate split points from these quantile sets. In XGBoost, for instance, a sophisticated quantile building algorithm is employed to identify the candidate split points for the decision trees. This method is often projected to yield better results when the computation is distributed. In this paper, we dispel the notion that these methods provide more accurate and scalable methods for building decision trees in a distributed manner. In a significant contribution, we show theoretically and empirically that choosing the split points uniformly at random provides the same or even better performance in terms of accuracy and computational efficiency. Hence, a simple random selection of points suffices for decision tree building compared to more sophisticated methods.

[Download paper here](https://arxiv.org/pdf/2108.08790.pdf)