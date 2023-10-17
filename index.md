---
layout: default
---

## Abstract

Graph neural networks (GNNs) have gained prominence in recommendation systems in recent years. By representing the user-item matrix as a bipartite and undirected graph, GNNs have demonstrated their potential to capture short- and long-distance user-item interactions, thereby learning more accurate preference patterns than traditional recommendation approaches. In contrast to previous tutorials on the same topic, this tutorial aims to present and examine three key aspects that characterize GNNs for recommendation: (i) the reproducibility of state-of-the-art approaches, (ii) the potential impact of graph topological characteristics on the performance of these models, and (iii) strategies for learning node representations when training features from scratch or utilizing pre-trained embeddings as additional item information (e.g., multimodal features). The goal is to provide three novel theoretical and practical perspectives on the field, currently subject to debate in graph learning but long been overlooked in the context of recommendation systems.

## Tutorial schedule

Total tutorial duration: 180 minutes

**Introduction and background** (Tommaso Di Noia): 20 minutes

+ Introduction and motivations of the tutorial: 5 minutes
+ Basics concepts of recommender systems & GNNs-based recommendation: 15 minutes

**Reproducibility**: 60 minutes

+ **[Hands-on]** Implementation of GNNs-based recsys in Elliot with PyG and reproducibility issues (Daniele Malitesta): 25 minutes
+ **[Hands-on]** Reproducing the results of state-of-the-art GNNs-based recommender systems (Claudio Pomo): 25 minutes
+ Performance comparison of GNNs-based approaches to traditional recommendation systems (Claudio Pomo): 10 minutes

**Break and Q&A**: 15 minutes

**Graph topology**: 30 minutes

+ Concepts and formulations of graph topological properties of the user-item graph (Tommaso Di Noia): 15 minutes
+ Impact of topological graph properties on the performance of GNNs-based recommender systems (Daniele Malitesta): 15 minutes

**Node representation**: 45 minutes

+ Design choices to train node embeddings from scratch (Claudio Pomo): 20 minutes
+ **[Hands-on]** Leveraging item's side-information (e.g., multimodal features) to represent node embeddings (Daniele Malitesta): 25 minutes

**Closing remarks and Q&A**: 10 minutes

## Useful material

### Slides

We are working on this...

### Codes

We are working on this...

### Papers

| Title | Paper                                                                                                                                                                                     | Slides                                                                                     | Code                                                           | Venue     | Year |
|---|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|----------------------------------------------------------------|----------|------|
| How Neighborhood Exploration Influences Novelty and Diversity in Graph Collaborative Filtering | [link](https://ceur-ws.org/Vol-3268/paper7.pdf)                                                                                                                                           | [link](https://drive.google.com/file/d/1oTLRPdW2DhY9WvPDYZmUVrvgvvcyd6n7/view?usp=sharing) | [link](https://github.com/sisinflab/Novelty-Diversity-Graph)   | MORS @ RecSys  | 2022 |
| Auditing Consumer- and Producer-Fairness in Graph Collaborative Filtering | [link](https://www.researchgate.net/publication/366200699_Auditing_Consumer-_and_Producer-Fairness_in_Graph_Collaborative_Filtering)                                                      | [link](https://drive.google.com/file/d/1EmxrMplPd96Pkm3MFQm_0OXdaKi3pkNW/view?usp=sharing) | [link](https://github.com/sisinflab/ECIR2023-Graph-CF)         | ECIR           | 2023 |
| An Out-of-the-Box Application for Reproducible Graph Collaborative Filtering extending the Elliot Framework | [link](https://graph-learning-benchmarks.github.io/assets/papers/glb2023/An_Out_of_the_Box_Application_for_Reproducible_Graph_Collaborative_Filtering_extending_the_Elliot_Framework.pdf) | [link](https://drive.google.com/file/d/1xd053ZUXyWQK2rIkI86AU3edorvYEPMK/view?usp=sharing) | [link](https://github.com/sisinflab/Graph-Demo)                | UMAP/GLB @ KDD | 2023 |
| Challenging the Myth of Graph Collaborative Filtering: a Reasoned and Reproducibility-driven Analysis | [link](https://arxiv.org/pdf/2308.00404.pdf)                                                                                                                                              | [link](https://www.slideshare.net/DanieleMalitesta/recsys2023-challenging-the-myth-of-graph-collaborative-filtering-a-reasoned-and-reproducibilitydriven-analysis)                                                                                | [link](https://github.com/sisinflab/Graph-RSs-Reproducibility) | RecSys         | 2023 |
| A Topology-aware Analysis of Graph Collaborative Filtering | [link](https://arxiv.org/pdf/2308.10778v1.pdf)                                                                                                                                            |                                                                                        | [link](https://github.com/sisinflab/Graph-Characteristics)     | arXiv          | 2023 |
| On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis | [link](https://arxiv.org/pdf/2308.12911.pdf)                                                                                                                                              |                                                                                       | [link](https://github.com/sisinflab/MultiMod-Popularity-Bias)  | MMIR @ MM      | 2023 |
| Formalizing Multimedia Recommendation through Multimodal Deep Learning | [link](https://arxiv.org/pdf/2309.05273.pdf)                                                                                                                                                                                  |                                                                                     | [link](https://github.com/sisinflab/Formal-MultiMod-Rec)                                                       | arXiv          | 2023 |

## Tutorial speakers

### Daniele Malitesta

_Ph.D. Candidate at Polytechnic University of Bari (Italy)_

Website: [https://danielemalitesta.github.io/](https://danielemalitesta.github.io/)

<img src="https://danielemalitesta.github.io/images/profilo_new.jpeg" alt="Daniele Malitesta"  width="200"/>

### Claudio Pomo

_Research Fellow at Polytechnic University of Bari (Italy)_

Website: [https://sisinflab.poliba.it/people/claudio-pomo/](https://sisinflab.poliba.it/people/claudio-pomo/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/image2-1197215127-scaled.jpg" alt="Claudio Pomo"  width="200"/>

### Tommaso Di Noia

_Professor of Computer Science at Polytechnic University of Bari (Italy)_

Website: [https://sisinflab.poliba.it/people/tommaso-di-noia/](https://sisinflab.poliba.it/people/tommaso-di-noia/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/t_dinoia-506699224-315x270.png" alt="Tommaso Di Noia"  width="200"/>