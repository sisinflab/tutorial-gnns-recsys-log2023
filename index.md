---
layout: default
---

## Abstract

Graph neural networks (GNNs) have gained prominence in recommendation systems in recent years. By representing the user-item matrix as a bipartite and undirected graph, GNNs have demonstrated their potential to capture short- and long-distance user-item interactions, thereby learning more accurate preference patterns than traditional recommendation approaches. In contrast to previous tutorials on the same topic, this tutorial aims to present and examine three key aspects that characterize GNNs for recommendation: (i) the reproducibility of state-of-the-art approaches, (ii) the potential impact of graph topological characteristics on the performance of these models, and (iii) strategies for learning node representations when training features from scratch or utilizing pre-trained embeddings as additional item information (e.g., multimodal features). The goal is to provide three novel theoretical and practical perspectives on the field, currently subject to debate in graph learning but long been overlooked in the context of recommendation systems.

## Tutorial schedule

Total tutorial duration: 180 minutes

<div class="button-container">
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/introduction/" class="button">Pt.0 Introduction</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/reproducibility/" class="button">Pt.1 Reproducibility</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/graphh_topology/" class="button">Pt.2 Graph Topology</a>
    <a href="https://sisinflab.github.io/tutorial-gnns-recsys-log2023/sections/node_representation/" class="button">Pt.3 Node Representation</a>
</div>

**Introduction and background** (Tommaso Di Noia): 20 minutes

+ Introduction and motivations of the tutorial: 5 minutes
+ Basics concepts of recommender systems & GNNs-based recommendation: 15 minutes

**Reproducibility**: 60 minutes

+ **[Hands-on #1]** Implementation and reproducibility of GNNs-based recsys in Elliot with PyG and reproducibility issues (Daniele Malitesta): 35 minutes
+ Performance comparison of GNNs-based approaches to traditional recommendation systems (Claudio Pomo): 25 minutes

**Break and Q&A**: 15 minutes

**Graph topology**: 30 minutes

+ Concepts and formulations of graph topological properties of the user-item graph (Tommaso Di Noia): 15 minutes
+ Impact of topological graph properties on the performance of GNNs-based recommender systems (Daniele Malitesta): 15 minutes

**Node representation**: 45 minutes

+ Design choices to train node embeddings from scratch (Claudio Pomo): 20 minutes
+ **[Hands-on #2]** Leveraging item's side-information (e.g., multimodal features) to represent node embeddings (Daniele Malitesta): 25 minutes

**Closing remarks and Q&A**: 10 minutes

## Useful material

### Slides

We are working on this...

### Codes

We are working on this...

### Papers

| Title | Paper                                                                                     | Slides                                                                                    | Code                                                           | Venue     | Year |
|---|-------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|----------------------------------------------------------------|----------|------|
| How Neighborhood Exploration Influences Novelty and Diversity in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MORS.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/MORS.pdf)   | [link](https://github.com/sisinflab/Novelty-Diversity-Graph)   | MORS @ RecSys  | 2022 |
| Auditing Consumer- and Producer-Fairness in Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/ECIR.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/ECIR.pdf)   | [link](https://github.com/sisinflab/ECIR2023-Graph-CF)         | ECIR           | 2023 |
| An Out-of-the-Box Application for Reproducible Graph Collaborative Filtering extending the Elliot Framework | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/UMAP.pdf)   | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/UMAP.pdf)   | [link](https://github.com/sisinflab/Graph-Demo)                | UMAP/GLB @ KDD | 2023 |
| Challenging the Myth of Graph Collaborative Filtering: a Reasoned and Reproducibility-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/RecSys.pdf) | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/slides/RecSys.pdf) | [link](https://github.com/sisinflab/Graph-RSs-Reproducibility) | RecSys         | 2023 |
| A Topology-aware Analysis of Graph Collaborative Filtering | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/arXiv.pdf)  |                                                                                           | [link](https://github.com/sisinflab/Graph-Characteristics)     | arXiv          | 2023 |
| On Popularity Bias of Multimodal-aware Recommender Systems: a Modalities-driven Analysis | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/MM.pdf)     |                                                                                           | [link](https://github.com/sisinflab/MultiMod-Popularity-Bias)  | MMIR @ MM      | 2023 |
| Formalizing Multimedia Recommendation through Multimodal Deep Learning | [link](https://sisinflab.github.io/tutorial-gnns-recsys-log2023/assets/papers/TORS.pdf)   |                                                                                           | [link](https://github.com/sisinflab/Formal-MultiMod-Rec)                                                       | arXiv          | 2023 |

## Tutorial speakers

### Daniele Malitesta

_Ph.D. Candidate at Polytechnic University of Bari (Italy)_

Email: [daniele.malitesta@poliba.it](mailto:daniele.malitesta@poliba.it)

Website: [https://danielemalitesta.github.io/](https://danielemalitesta.github.io/)

<img src="https://danielemalitesta.github.io/images/profilo_new.jpeg" alt="Daniele Malitesta"  width="200"/>

### Claudio Pomo

_Research Fellow at Polytechnic University of Bari (Italy)_

Email: [claudio.pomo@poliba.it](mailto:claudio.pomo@poliba.it)

Website: [https://sisinflab.poliba.it/people/claudio-pomo/](https://sisinflab.poliba.it/people/claudio-pomo/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/image2-1197215127-scaled.jpg" alt="Claudio Pomo"  width="200"/>

### Tommaso Di Noia

_Professor of Computer Science at Polytechnic University of Bari (Italy)_

Email: [tommaso.dinoia@poliba.it](mailto:tommaso.dinoia@poliba.it)

Website: [https://sisinflab.poliba.it/people/tommaso-di-noia/](https://sisinflab.poliba.it/people/tommaso-di-noia/)

<img src="https://sisinflab.poliba.it/wp-content/uploads/2020/07/t_dinoia-506699224-315x270.png" alt="Tommaso Di Noia"  width="200" />
