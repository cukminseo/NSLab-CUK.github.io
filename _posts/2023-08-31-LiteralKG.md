---
layout: post
title: LiteralKG, a knowledge graph embedding model that could learn different types of Literal information and graph structure and fuse them into unified representations.
date:   2023-08-18 00:00:00 +0900
tags:   Release
published: true
description: The Network Science Lab at the Catholic University of Korea releases LiteralKG, a novel Literal-aware Medical Knowledge Graph Embedding Model specialising in fusing Literal information and entity relations into unified vector representations.
---

We present [LiteralKG](https://github.com/NSLab-CUK/LiteralKG), a novel Literal-aware Medical Knowledge Graph Embedding Model, integrating both Literal information and entity relations into unified representations and developed by NS Lab, CUK based on pure PyTorch backend.

<p align="center">
  <img src="/images/LiteralKG.jpg" alt="LiteralKG Architecture" width="800">
  <br>
  <b></b> The overall architecture of LiteralKG.
</p>

Over the past few years, Knowledge Graph (KG) embedding has been used to benefit the diagnosis of animal diseases by analyzing electronic medical records (EMRs), such as notes and veterinary records. However, learning representations to capture entities and relations with literal information in KGs is challenging as the KGs show heterogeneous properties and various types of literal information. Meanwhile, the existing methods mostly aim to preserve graph structures surrounding target nodes without considering different types of literals, which could also carry significant information. We propose **LiteralKG**, a knowledge graph embedding model for efficiently diagnosing animal diseases, which could learn various types of literal information and graph structure and fuse them into unified representations. Specifically, we construct a knowledge graph that is built from EMRs along with literal information collected from various animal hospitals. We then fuse different types of entities and node feature information into unified vector representations through gate networks. Finally, we propose a self-supervised learning task to learn graph structure in pretext tasks and then towards various downstream tasks. Experimental results on link prediction tasks demonstrate that our model outperforms the baselines that consist of state-of-the-art models.

## A short description of **LiteralKG**:

- We construct a medical knowledge graph that comprises 595,172 entities and 16 relation types from various EMRs.
- **LiteralKG** could learn different types of literal information and graph structure and then fuse them into unified representations.
- **LiteralKG**, a self-supervised learning framework for Knowledge Graph, that could learn the graph structure from pretext tasks to generate representations, and then the pre-trained model is used for downstream tasks to predict animal diseases.
- The experimental results on the KG with different types of GNN aggregators and residual connection and identity mapping show the superiority of **LiteralKG** over baselines.

## The **LiteralKG** is available at:
* [![GitHub](https://img.shields.io/badge/GitHub-Data%20&%20Code-9B9B9B?style=flat-square&logo=GitHub)](https://github.com/NSLab-CUK/LiteralKG)
* [![arXiv](https://img.shields.io/badge/arXiv-2308.09517-b31b1b?style=flat-square&logo=arxiv&logoColor=red)](https://arxiv.org/abs/2308.09517)


## Citing **LiteralKG**

Please cite our [paper](https://arxiv.org/abs/2308.09517) if you find *UGT* useful in your work:
```
@misc{hoang2023ugt,
      title={Companion Animal Disease Diagnostics based on Literal-aware Medical Knowledge Graph Representation Learning}, 
      author={Van Thuy Hoang, Sang Thanh Nguyen, Sangmyeong Lee, Jooho Lee, Luong Vuong Nguyen, and O-Joun Lee},
      year={2023},
      eprint={2308.09517},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

:page_facing_up::woman_technologist::bookmark_tabs::label::black_nib:	

## Contributors

<a href="https://github.com/NSLab-CUK/LiteralKG/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=NSLab-CUK/Unified-Graph-Transformer" />
</a>

***

<a href="https://nslab-cuk.github.io/"><img src="https://github.com/NSLab-CUK/NSLab-CUK/raw/main/Logo_Dual_Wide.png"/></a>

***

