---
title: "Region2vec: Community detection on spatial networks using graph embedding with node attributes and spatial interactions"
collection: publications
permalink: /publication/paper-3
excerpt: ''
date: 2022-11-1
venue: 'Proceedings of the 30th International Conference on Advances in Geographic Information Systems'
authors: 'Yunlei Liang, Jiawei Zhu, <strong>Wen Ye</strong>, Song Gao'
---

Community Detection algorithms are used to detect densely connected components in complex networks and reveal underlying relationships among components. As a special type of networks, spatial networks are usually generated by the connections among geographic regions. Identifying the spatial network communities can help reveal the spatial interaction patterns, understand the hidden regional structures and support regional development decision-making. Given the recent development of Graph Convolutional Networks (GCN) and its powerful performance in identifying multi-scale spatial interactions, we proposed an unsupervised GCN-based community detection method region2vec on spatial networks. Our method first generates node embeddings for regions that share common attributes and have intense spatial interactions, and then applies clustering algorithms to detect communities based on their embedding similarity and spatial adjacency. Experimental results show that while existing methods trade off either attribute similarities or spatial interactions for one another, region2vec maintains a great balance between both and performs the best when one wants to maximize both attribute similarities and spatial interactions within communities.

[Download paper here](https://dl.acm.org/doi/abs/10.1145/3557915.3560974)