---
layout: page
title: NS-CUK Open Source Projects
permalink: /open-source-projects/
image: CUK_4Seasons.jpg
description: Open source projects run by members and collaborators of the Network Science Lab at the Catholic University of Korea
toc: true
toc_sticky: true
toc_label: "Table of Contents"
---

This page serves as a repository for open source projects run by members and collaborators of the Network Science Lab. We aim to improve the availability of open source implementations and the reproducibility of experiments in artificial intelligence and data science studies.

***

<h5>Table of Contents</h5>
* TOC
{:toc}

***
# Graph Representation Learning

The following datasets are available via [our official GitHub account](https://github.com/NSLab-CUK/). 

***
## Graph Neural Networks and Graph Transformers

### CGT, A Novel Graph Transformer Model for Mitigating Degree Biases in Message Passing Mechanism

* **Description:** We present CGT, a novel Graph Transformer model specialised in mitigating degree biases in Message Passing mechanism. We utilize community structures to address node degree biases in message-passing (MP) via learnable graph augmentations and novel graph transformers. Recent augmentation-based methods showed that MP neural networks often perform poorly on low-degree nodes, leading to degree biases due to a lack of messages reaching low-degree nodes. Despite their success, most methods use heuristic or uniform random augmentations, which are non-differentiable and may not always generate valuable edges for learning representations. In this paper, we propose Community-aware Graph Transformers, namely CGT, to learn degree-unbiased representations based on learnable augmentations and graph transformers by extracting within community structures. We first design a learnable graph augmentation to generate more within-community edges connecting low-degree nodes through edge perturbation. Second, we propose an improved self-attention to learn underlying proximity and the roles of nodes within the community. Third, we propose a self-supervised learning task that could learn the representations to preserve the global graph structure and regularize the graph augmentations. Extensive experiments on various benchmark datasets showed CGT outperforms state-of-the-art baselines and significantly improves the node degree biases.
* **Cite as:** Van Thuy Hoang, O-Joun Lee: Mitigating Degree Biases in Message Passing Mechanism by Utilizing Community Structures. arXiv preprint 12/2023; arXiv:2312.16788. (Preprint)
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Community-aware-Graph-Transformer)

### UGT, A Novel Graph Transformer Model for Unifying Local and Global Graph Structural Features

* **Description:** Over the past few years, graph neural networks and graph transformers have been successfully used to analyze graph-structured data, mainly focusing on node classification and link prediction tasks. However, the existing studies mostly only consider local connectivity while ignoring long-range connectivity and the roles of nodes. We propose Unified Graph Transformer Networks (UGT) that effectively integrate local and global structural information into fixed-length vector representations. UGT learns local structure by identifying the local substructures and aggregating features of the k-hop neighborhoods of each node. We construct virtual edges, bridging distant nodes with structural similarity to capture the long-range dependencies. UGT learns unified representations through self-attention, encoding structural distance and p-step transition probability between node pairs. Furthermore, we propose a self-supervised learning task that effectively learns transition probability to fuse local and global structural features, which could then be transferred to other downstream tasks. Experimental results on real-world benchmark datasets over various downstream tasks showed that UGT significantly outperformed baselines that consist of state-of-the-art models. In addition, UGT reaches the third-order Weisfeiler-Lehman power to distinguish non-isomorphic graph pairs.
* **Cite as:** Van Thuy Hoang, O-Joun Lee: Transitivity-Preserving Graph Representation Learning for Bridging Local Connectivity and Role-based Similarity. The 38th AAAI Conference on Artificial Intelligence (AAAI 2024), Vancouver, Canada; 02/2024.
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Unified-Graph-Transformer)

### Connector, A Novel Unified Framework for Graph Representation Learning

* **Description:** We present Connector, a comprehensive graph representation learning framework developed primarily in Python using the PyTorch library. Connector Ver. 0.5 is a test release that will be further developed to enable researchers from different fields to apply graph representation learning models to their research. Connector consists of three main modules: graph data loaders, base model and graph representation learning modules. The graph loader modules introduce four graph loaders, namely homogeneous, heterogeneous, signed graph and knowledge graph loaders, which allow researchers to easily handle different types of graphs. By loading graph data, researchers can build and manipulate datasets with different file structures. The base model module includes different types of neural network layers, aggregators and sampling techniques for graphs to build common tasks such as loading models and loading/saving parameters.
* **Cite as:** Thanh Sang Nguyen, Jooho Lee, Van Thuy Hoang, O-Joun Lee: Connector 0.5: A unified framework for graph representation learning. arXiv preprint 04/2023; arXiv:2304.13195. (Preprint)
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Connector)

***
## Lecture Materials

### Programming & Designing AI - Spring 2024

* **Description:** This repository is for archiving the Programming & Designing AI (04576-02) class repository for the Department of Artificial Intelligence at the Catholic University of Korea. This platform is dedicated to sharing and archiving lecture materials such as practices, assignments, and sample codes for the class.
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Programming-and-Designing-AI-Spring-2024)

### Graph Mining - Spring 2024

* **Description:** This repository is for archiving the Graph Mining class (06837-01) of the Department of Artificial Intelligence at the Catholic University of Korea. This platform is dedicated to sharing and archiving lecture materials such as exercises, assignments, and sample code for the class.
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Graph-Mining-Spring-2024)

### Graph Neural Networks - Fall 2023

* **Description:** This repository is for archiving the Graph Neural Networks class (06838-01) of the Department of Artificial Intelligence at the Catholic University of Korea. This platform is dedicated to sharing and archiving lecture materials such as exercises, assignments, and sample code for the class.
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Graph-Neural-Networks-Fall-2023)

### Graph Mining - Spring 2023

* **Description:** This repository is for archiving the Graph Mining class (06837-01) of the Department of Artificial Intelligence at the Catholic University of Korea. This platform is dedicated to sharing and archiving lecture materials such as exercises, assignments, and sample code for the class.
* **Repository:** [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/Graph-Mining-Spring-2023)




