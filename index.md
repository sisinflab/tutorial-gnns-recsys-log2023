---
layout: default
---

## Abstract

Graph neural networks (GNNs) have gained prominence in recommendation systems in recent years. By representing the user-item matrix as a bipartite and undirected graph, GNNs have demonstrated their potential to capture short- and long-distance user-item interactions, thereby learning more accurate preference patterns than traditional recommendation approaches. In contrast to previous tutorials on the same topic, this tutorial aims to present and examine three key aspects that characterize GNNs for recommendation: (i) the reproducibility of state-of-the-art approaches, (ii) the potential impact of graph topological characteristics on the performance of these models, and (iii) strategies for learning node representations when training features from scratch or utilizing pre-trained embeddings as additional item information (e.g., multimodal features). The goal is to provide three novel theoretical and practical perspectives on the field, currently subject to debate in graph learning but long been overlooked in the context of recommendation systems.

## Tutorial schedule

Total tutorial duration: 180 minutes

**Introduction and background** (Tommaso Di Noia): 20 minutes

+ Introduction and motivations of the tutorial: 5 minutes
+ Basics concepts of recommender systems \& GNNs-based recommendation: 15 minutes

**Reproducibility**: 60 minutes

+ **[Hands-on]** Implementation of GNNs-based recsys in Elliot with PyG and reproducibility issues (Daniele Malitesta): 25 minutes
+ **[Hands-on]** Reproducing the results of state-of-the-art GNNs-based recommender systems (Claudio Pomo): 25 minutes
+ Performance comparison of GNNs-based approaches to traditional recommendation systems (Claudio Pomo): 10 minutes

**Break and Q\&A**: 15 minutes

**Graph topology**: 30 minutes

+ Concepts and formulations of graph topological properties of the user-item graph (Tommaso Di Noia): 15 minutes
+ Impact of topological graph properties on the performance of GNNs-based recommender systems (Daniele Malitesta): 15 minutes

**Node representation**: 45 minutes

+ Design choices to train node embeddings from scratch (Claudio Pomo): 20 minutes
+ **[Hands-on]** Leveraging item's side-information (e.g., multimodal features) to represent node embeddings (Daniele Malitesta): 25 minutes

**Closing remarks and Q\&A**: 10 minutes