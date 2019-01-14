# Awesome paper list
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A collection of graph embedding, deep learning, recomendation papers with reference implementations

<p align="center">
  <img width="460" src="Word Art.png">
  <figcaption><font size="2">word cloud</font></figcaption>
</p>

**Table of Contents**
[TOC]
1. [Recomendation](##Recomendation)
2. [Graph](##Graph)
3. [Bayesian Deep Learning](##BayesianDeepLearning)
4. [Datasets](##Datasets)



## Recomendation

### Largel Scale
- **Dynamic Attention Deep Model for Article Recommendation by Learning Human Editors’ Demonstration (KDD 2017)**
  - Xuejian Wang, Lantao Yu, Kan Ren
  - [Paper](https://dl.acm.org/citation.cfm?id=3098096)

### CTR Based
- **[DKN: Deep Knowledge-Aware Network for News Recommendation (WWW 2018)](./paper-note/DKN-Deep-Knowledge-Aware-Network-for-News-Recommendation.md)**
  - [Hongwei Wang], Fuzheng Zhang, Xing Xie, Minyi Guo
  - [Paper](https://dl.acm.org/citation.cfm?id=3186175)
  - [tensorflow](https://github.com/hwwang55/DKN)


- **Deep Interest Network for Click-Through Rate Prediction (KDD 2018)**
  - Guorui Zhou, Chengru Song, Xiaoqiang Zhu, Ying Fan, Han Zhu, Xiao Ma, Yanghui Yan, Junqi Jin, Han Li, Kun Gai
  - [Paper](https://arxiv.org/abs/1706.06978)
  - [tensorflow](https://github.com/zhougr1993/DeepInterestNetwork)



### Normal
- **Learning Consumer and Producer Embeddings for User-Generated Content Recommendation (Recsys 2018)**
  - [Wang-Cheng Kang], [Julian McAuley]
  - [Paper](https://arxiv.org/abs/1809.09739)

- **Spectral Collaborative Filtering (Recsys 2018)**
  - [Lei Zheng], Chun-Ta Lu, Fei Jiang, Jiawei Zhang, Philip S. Yu
  - [Paper](https://arxiv.org/abs/1808.10523v1)

- **Music Recommendation by Uni fi ed Hypergraph : Combining Social Media Information and Music Content (MM 2010)**
  - Bu Jiajun, Tan Shulong, [Xiaofei He]
  - [Paper](https://dl.acm.org/citation.cfm?id=1874005)

- **Heterogeneous hypergraph embedding for document recommendation (Neurocomputing 2016)**
  - Yu Zhu, Ziyu Guan, Shulong Tan, Haifeng Liu, Deng Cai, [Xiaofei He]
  - [paper](https://www.sciencedirect.com/science/article/pii/S0925231216307755)

### News recomendation

- **News Recommendation via Hypergraph Learning: Encapsulation of User Behavior and News Content (WSDM 2013)**
  - Lei Li, Tao Li
  - [Paper](https://dl.acm.org/citation.cfm?id=2433436)

- **Weave & Rec : A Word Embedding based 3-D Convolutional Network for News Recommendation (CIKM 2018 short paper)**
  - Dhruv Khattar, Vaibhav Kumar, Vasudeva Varma, Manish Gupta
  - [Paper](https://dl.acm.org/citation.cfm?id=3269307&dl=ACM&coll=DL)
  - [keras](https://github.com/dhruvkhattar/WE3CN)


### Review Based
- **A3NCF: An Adaptive Aspect Attention Model for Rating Prediction (IJCAI 2018)**
  - Zhiyong Cheng, Ying Ding, [Xiangnan He], Lei Zhu, Xuemeng Song, Mohan Kankanhalli
  - [Paper](https://www.comp.nus.edu.sg/~xiangnan/papers/ijcai18-A3NCF.pdf)
  - [Keras](https://github.com/hustlingchen/A3NCF)
### Expainable
- **Explainable Reasoning over Knowledge Graphs for Recommendation**
- **Explainable Recommendation Through Attentive Multi-View Learning (AAAI 2018)**
- **RippleNet : Propagating User Preferences on the Knowledge Graph for Recommender Systems (CIKM 2018)**
## Graph

### Graph Convolutional Embedding Theory
- **Survey: Representation Learning on Graphs: Methods and Applications**
  - [William L. Hamilton], [Rex Ying], [Jure Leskovec]
  - [Paper](https://arxiv.org/abs/1709.05584)
- **A Comprehensive Survey on Graph Neural Networks**
  - Zonghan Wu ,Philip S. Yu
  - [Paper](https://arxiv.org/abs/1901.00596?context=cs)
- **SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS (ICLR 2017)**
  - [Thomas N. Kipf],  [Max Welling]
  - [Paper](https://arxiv.org/abs/1609.02907)
  - [tensorflow](https://github.com/tkipf/gcn)
- **GraphSAGE: Inductive Representation Learning on Large Graphs (NIPS 2017)**
  - [William L. Hamilton], [Rex Ying], [Jure Leskovec]
  - [Paper](https://arxiv.org/pdf/1706.02216.pdf)
  - [code](http://snap.stanford.edu/graphsage/#code)
- **[HOW POWERFUL ARE GRAPH NEURAL NETWORKS (ICLR 2019)](./paper-note/HOW-POWERFUL-ARE-GRAPH-NEURAL-NETWORKS.md)**
  - Keyulu Xu, Weihua Hu, [Jure Leskovec], Stefanie Jegelka
  - [Openreview](https://openreview.net/forum?id=ryGs6iA5Km)
- **GLoMo: Unsupervisedly Learned Relational Graphs as Transferable Representations (NIPS 2018)**
  - Zhilin Yang, Jake Zhao, Bhuwan Dhingra, Kaiming He, William W. Cohen, Ruslan Salakhutdinov, Yann LeCun
  - [Paper](https://arxiv.org/abs/1806.05662)

### Graph Convolutional Application
- **Graph Convolutional Matrix Completion (KDD deepalearningday 2018)**
  - Rianne van den Berg, [Thomas N. Kipf],  [Max Welling]
  - [Paper](https://arxiv.org/pdf/1706.02263.pdf)
  - [tensorflow](https://github.com/riannevdberg/gc-mc)

- **Hierarchical Graph Representation Learning with Differentiable Pooling (NIPS 2018)**
  - [Rex Ying], Jiaxuan You, Christopher Morris, Xiang Ren, William L. Hamilton, Jure Leskovec
  - [Paper](https://dl.acm.org/citation.cfm?id=2433436)

- **Modeling Relational Data with Graph Convolutional Networks (ESWC 2018)**
  - Michael Schlichtkrull, [Thomas N. Kipf], Peter Bloem, Rianne van den Berg, Ivan Titov, [Max Welling]
  - [Paper](https://arxiv.org/abs/1703.06103)
  - [keras](https://github.com/tkipf/relational-gcn)
  - [tensorflow](https://github.com/MichSchli/RelationPrediction)

- **Graph Convolutional Neural Networks for Web-Scale Recommender Systems (KDD 2018)**
  - [Rex Ying], Ruining He, Kaifeng Chen, Pong Eksombatchai, William L. Hamilton, [Jure Leskovec]
  - [Paper](https://dl.acm.org/citation.cfm?id=2433436)

- **Graph Attention Networks (ICLR 2018)**
  - Petar Veliˇckovi´, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Li`, Yoshua Bengio
  - [Paper](https://arxiv.org/abs/1710.10903)
  - [tensorflow](https://github.com/PetarV-/GAT)
### Knowledge Graph
- **Translating Embeddings for Modeling Multi-relational Data (NIPS 2013)**
  - Antoine Bordes, Nicolas Usunier, Alberto Garcia-Duran, Jason Weston, Oksana Yakhnenko
  - [Paper](https://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data)
  - [Code for TransE, TransH, TransR and PTransE](https://github.com/thunlp/KB2E)

- **[SimplE Embedding for Link Prediction in Knowledge Graphs (NIPS 2013)](./paper-note/Structural-Deep-Embedding-for-Hyper-Networks.md)**
  - [Seyed Mehran Kazemi], David Poole
  - [Paper](https://arxiv.org/abs/1802.04868)
  - [tensorflow](https://github.com/Mehran-k/SimplE)

- **RippleNet: Propagating User Preferences on the Knowledge Graph for Recommender Systems (CIKM 2018)**
  - [Hongwei Wang], Fuzheng Zhang, Jialin Wang, Miao Zhao, Wenjie Li, [Xing Xie], Minyi Guo
  - [Paper](https://arxiv.org/abs/1803.03467)
  - [tensorflow](https://github.com/hwwang55/RippleNet)

- **[DKN: Deep Knowledge-Aware Network for News Recommendation (WWW 2018)](./paper-note/DKN-Deep-Knowledge-Aware-Network-for-News-Recommendation.md)**
  - [Hongwei Wang], Fuzheng Zhang, Xing Xie, Minyi Guo
  - [Paper](https://dl.acm.org/citation.cfm?id=3186175)
  - [tensorflow](https://github.com/hwwang55/DKN)

- **Convolutional 2D Knowledge Graph Embeddings (AAAI 2017)**
  - [Tim Dettmers], Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel
  - [Paper](https://arxiv.org/abs/1707.01476)
  - [Pytorch](https://github.com/TimDettmers/ConvE)
### HyperGraph

- **Hypergraph Neural Networks (AAAI 2019)**
  -  Yifan Feng, Haoxuan You, Zizhao Zhang, Rongrong Ji, [Yue Gao]
  - [Paper](https://arxiv.org/abs/1809.09401)
  - [pytorch](https://github.com/Yue-Group/HGNN)

- **[Structural Deep Embedding for Hyper-Networks (AAAI 2018)](./paper-note/Structural-Deep-Embedding-for-Hyper-Networks.md)**
  - Ke Tu, [Peng Cui], Xiao Wang, Fei Wang, Wenwu Zhu
  - [Paper](https://arxiv.org/abs/1711.10146)
  - [tensorflow](https://github.com/tadpole/DHNE)

- **Exploiting Relational Information in Social Networks using Geometric Deep Learning on Hypergraphs**

- **Modeling Multi-way Relations with Hypergraph Embedding (CIKM 2018 short paper)**
  - Chia-An Yu, Ching-Lun Tai, Tak-Shing Chan, Yi-Hsuan Yang
  - [Paper](https://dl.acm.org/citation.cfm?id=3269274)
  - [matlab](http://github.com/chia-an/HGE)

### Heterogeneous information network

- **Meta-Graph Based Recommendation Fusion over Heterogeneous Information Networks (KDD 2018)**
  - [Huan Zhao], anming Yao, Jianda Li, Yangqiu Song and Dik Lun Lee
  - [Paper](http://www.cse.ust.hk/~hzhaoaf/data/kdd17-paper.pdf)
  - [python](https://github.com/HKUST-KnowComp/FMG)

- **Leveraging Meta-path based Context for Top- N Recommendation with A Neural Co-Attention Model (KDD 2018)**
  - Binbin Hu, [Chuan Shi], Wayne Xin Zhao, [Philip S. Yu]
  - [Paper](http://shichuan.org/doc/47.pdf)
  - [tensorflow&keras](https://github.com/librahu/MCRec)
  - [data](https://github.com/librahu/Heterogeneous-Information-Network-Datasets-for-Recommendation)


- **Aspect-Level Deep Collaborative Filtering via Heterogeneous Information Networks (IJCAI 2018)**
  - Xiaotian Han, [Chuan Shi], Senzhang Wang, [Philip S. Yu], Li Song
  - [Paper](http://shichuan.org/doc/46.pdf)
  - [tensorflow](https://github.com/ahxt/NeuACF)

- **Deep Collective Classification in Heterogeneous Information Networks (WWW 2018)**
  - [Paper](https://dl.acm.org/authorize?N655839)
  - [keras](https://github.com/zyz282994112/GraphInception)

  

  

  **other implement resource**:

  - [gated-graph-neural-network-samples](https://github.com/Microsoft/gated-graph-neural-network-samples)
  - [Graph-neural-networks jupyter tutorial](https://github.com/SeongokRyu/Graph-neural-networks)
  - [Deep Graph Library (DGL) Python package](https://docs.dgl.ai/index.html)
  - [gnn-benchmark](https://github.com/shchur/gnn-benchmark)
  - [pytorch_geometric](https://github.com/rusty1s/pytorch_geometric)

  **Other reading materials**:

  - [Tsinghua University Graph papers reading list](https://github.com/thunlp/GNNPapers)


## BayesianDeepLearning
- **Recent Advances in Autoencoder-Based Representation Learning (NIPS 2018)**
  - Michael Tschannen, Olivier Bachem, Mario Lucic
  - [Paper](https://arxiv.org/abs/1812.05069)

## Hyperbolic embedding

- **Poincaré Embeddings for Learning Hierarchical Representations (NIPS 2017)**
  - [Maximilian Nickel], Kiela Douwe
  - [paper](https://arxiv.org/abs/1705.08039)
  - [pytorch](https://github.com/facebookresearch/poincare-embeddings)
- **Hyperbolic Neural Networks(NIPS 2018)**
  - [Octavian Eugen Ganea], Hofmann, Thomas
  - [paper](https://arxiv.org/abs/1805.09112)
  - [tensorflow](https://github.com/dalab/hyperbolic_nn)


## Datasets

### homegenerous graph dataset
- **PubMed Diabetes**
  - The Pubmed Diabetes dataset consists of 19717 scientific publications from PubMed database pertaining to diabetes classified into one of three classes. The citation network consists of 44338 links. Each publication in the dataset is described by a TF/IDF weighted word vector from a dictionary which consists of 500 unique words. The README file in the dataset provides more details.
  - Download Link:
    - https://linqs-data.soe.ucsc.edu/public/Pubmed-Diabetes.tgz
  - Related Papers:
    - Galileo Namata, et. al. "Query-driven Active Surveying for Collective Classification." MLG. 2012.

- **Cora**
  - The Cora dataset consists of 2708 scientific publications classified into one of seven classes. The citation network consists of 5429 links. Each publication in the dataset is described by a 0/1-valued word vector indicating the absence/presence of the corresponding word from the dictionary. The dictionary consists of 1433 unique words. The README file in the dataset provides more details.
  - Download Link:
    - https://linqs-data.soe.ucsc.edu/public/lbc/cora.tgz
  - Related Papers:
    - Qing Lu, and Lise Getoor. "Link-based classification." ICML, 2003.
    - Prithviraj Sen, et al. "Collective classification in network data." AI Magazine, 2008.

other useful datasets link:
- citation dataset
  - https://linqs.soe.ucsc.edu/data


### heteregeneous graph datasets

- **IMDB Datasets**
  - MovieLens Latest Dataset which consists of 33,000 movies. And it contains four types of nodes: movie, director, actor and actress, connected by two types of relations/link: directed link and actor/actress staring link. Each movie is assigned with a set of class labels, indicating generes of the movie. For each movie, we extract a bag of words vector of all the plot summary about the movie as local features, which include 1000 words.
  - Download Link:
    - https://github.com/trangptm/Column_networks/tree/master/data
  - Related Papers:
    - T. Pham, et al. "Column networks for collective classification." In AAAI, 2017.
    - Zhang, Yizhou et al. "Deep Collective Classification in Heterogeneous Information Networks" In WWW, 2018.


other useful dataset links

- processed Datasets
  - https://github.com/librahu/Heterogeneous-Information-Network-Datasets-for-Recommendation-and-Network-Embedding/blob/master/README.md

[Octavian Eugen Ganea]: http://people.inf.ethz.ch/ganeao/
[Maximilian Nickel]: https://mnick.github.io/project/geometric-representation-learning/

[Chuan Shi]: http://shichuan.org/ShiChuan_ch.html
[Xing Xie]: https://www.microsoft.com/en-us/research/people/xingx/#!representative-publications
[Tim Dettmers]: http://timdettmers.com/about/
[Seyed Mehran Kazemi]: https://www.cs.ubc.ca/~smkazemi/
[Xiangnan He]: https://www.comp.nus.edu.sg/~xiangnan/
[Hongwei Wang]: https://hwwang55.github.io/
[Peng Cui]: http://pengcui.thumedialab.com/
[William L. Hamilton]: https://williamleif.github.io/
[Yue Gao]: http://www.gaoyue.org/tsinghua/pubs/index.htm
[Xiaofei He]: http://www.cad.zju.edu.cn/home/xiaofeihe/
[Thomas N. Kipf]: https://tkipf.github.io/
[Max Welling]: https://staff.fnwi.uva.nl/m.welling/
[Rex Ying]: https://cs.stanford.edu/people/rexy/
[Lei Zheng]: https://lzheng21.github.io/publications/
[Jure Leskovec]: https://cs.stanford.edu/~jure/
[Wang-Cheng Kang]: http://cseweb.ucsd.edu/~wckang/
[Julian McAuley]: https://cseweb.ucsd.edu/~jmcauley/
