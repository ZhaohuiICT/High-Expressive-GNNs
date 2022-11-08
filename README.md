# High-Expressive-GNNs

> A curated list of awesome high expressive GNNs for graph classification. (Actively keep updating)


## Contents
- [Survey Papers](#survey-papers)
- [Weisfeiler-Leman](#weisfeiler-leman)
- [High-order WL-based Methods](#high-order-WL-based-methods)
- [Augmented feature-based Methods](#augmented-feature-based-methods)
    - [Random Feature](#random-feature)
    - [Distance Encoding](#distance-encoding)
- [Subgraph-based Methods](#subgraph-based-methods)
- [k-hop Message Passing GNNs](#k-hop-message-passing-gnns)
- [WL meets Path/Random Walk](#WL-meets-Path/Random-Walk)
- [Equivariant Graph Networks](#Equivariant-Graph-Networks)
- [Expressiveness & Efficiency (Complexity) Tradeoff](#Expressiveness-&-Efficiency-(Complexity)-Tradeoff)



## Survey Papers
- [A Survey on The Expressive Power of Graph Neural Networks](https://arxiv.org/pdf/2003.04078.pdf) *Ryoma Sato.* 2020.
- [The Expressive Power of Graph Neural Networks](https://graph-neural-networks.github.io/static/file/chapter5.pdf) *Pan Li et al.* 2022.
- [A Theoretical Comparison of Graph Neural Network Extensions](https://arxiv.org/pdf/2201.12884.pdf) *Pal Andras Papp et al.* 2022. 


## Weisfeiler-Lehman 
- [The reduction of a graph to canonical form and the algebra which appears therein](https://www.iti.zcu.cz/wl2018/pdf/wl_paper_translation.pdf) *Boris Weisfeiler and Andrey Lehman* 1968.
- [Weisfeiler-Lehman Graph Kernels](https://www.jmlr.org/papers/volume12/shervashidze11a/shervashidze11a.pdf) *Nino Shervashidze.* 2011.
- [Power and Limits of the Weisfeiler-Leman Algorithm](https://publications.rwth-aachen.de/record/785831/files/785831.pdf) *Sandra Kiefer.* 2020.
- [The Power of the Weisfeiler-Leman Algorithm for Machine Learning with Graphs](https://arxiv.org/pdf/2105.05911.pdf) *Christopher Morris et al.* 2021.
- [Weisfeiler and Leman go Machine Learning: The Story so far](https://arxiv.org/pdf/2112.09992.pdf) *Christopher Morris et al.* 2021.
- [A Short Tutorial on The Weisfeiler-Lehman Test And Its Variants](https://arxiv.org/pdf/2201.07083.pdf) *Ningyuan Huang et al.* 2022.

- [How Powerful are Graph Neural Networks?](https://openreview.net/pdf?id=ryGs6iA5Km) *Keyulu Xu et al.* ICLR 2019.[[code](https://github.com/weihua916/powerful-gnns)]


## Higher-order WL-based Methods
- [Weisfeiler and Leman Go Neural: Higher-Order Graph Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/4384) *Christopher Morris et al.* AAAI 2019. [[code](https://github.com/chrsmrrs/k-gnn)] (**k-GNN**)
- [Provably Powerful Graph Networks](https://proceedings.neurips.cc/paper/2019/file/bb04af0f7ecaee4aae62035497da1387-Paper.pdf) *Haggai Maron et al.* NeurIPS 2019. [[code](https://github.com/hadarser/ProvablyPowerfulGraphNetworks_torch)] (**PPGN**)

## Augmented Feature-based Methods

### Random Feature
- [What graph neural networks cannot learn: depth vs width](https://openreview.net/pdf?id=B1l2bp4YwS) *Andreas Loukas* ICLR 2020. 
- [Random Features Strengthen Graph Neural Networks](https://epubs.siam.org/doi/epdf/10.1137/1.9781611976700.38) *Ryoma Sato et al.* SIAM 2021. [[code](https://github.com/joisino/random-features)]
- [The Surprising Power of Graph Neural Networks with Random Node Initialization](https://www.ijcai.org/proceedings/2021/0291.pdf) *Ralph Abboud et al.* IJCAI 2021. [[code](https://github.com/ralphabb/GNN-RNI)]

### Distance Encoding
- [Distance Encoding: Design Provably More Powerful Neural Networks for Graph Representation Learning](https://proceedings.neurips.cc/paper/2020/file/2f73168bf3656f697507752ec592c437-Paper.pdf) *Pan Li et al.* NeurIPS 2020. [[code](https://github.com/snap-stanford/distance-encoding)] (**DE-GNN**)
- [Equivariant and Stable Positional Encoding for More Powerful Graph Neural Networks](https://openreview.net/pdf?id=e95i1IHcWj) *Haorui Wang et al.* ICLR 2022. [[code](https://github.com/Graph-COM/PEG)] (**PEG**)

### Substructure Encoding
- [Can Graph Neural Networks Count Substructures?](https://proceedings.neurips.cc/paper/2020/file/75877cb75154206c4e65e76b88a12712-Paper.pdf) *Zhengdao Chen et al.* NIPS 2020. [[code](https://github.com/leichen2018/GNN-Substructure-Counting)]
- [Improving Graph Neural Network Expressivity via Subgraph Isomorphism Counting](https://arxiv.org/pdf/2006.09252.pdf) *Bouritsas et al.* TPAMI 2022. [[code](https://github.com/gbouritsas/GSN)] (**GSN**)




## Subgraph-based Methods
- [Nested Graph Neural Networks](https://openreview.net/pdf?id=7_eLEvFjCi3) *Muhan Zhang et al.* NeurIPS 2021. [[code](https://github.com/muhanzhang/NestedGNN)] (**NGNN**)
- [Ego-GNNs: Exploiting Ego Structures in Graph Neural Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9414015) *Dylan Sandfelder et al.* ICASSP 2021. (**Ego-GNN**)
- [From Stars to Subgraphs: Uplifting Any GNN with Local Structure Awareness](https://openreview.net/pdf?id=Mspk_WYKoEH) *Lingxiao Zhao et al.* ICLR 2022. [[code](https://github.com/LingxiaoShawn/GNNAsKernel)] (**GNN-AK**)
- [Equivariant Subgraph Aggregation Networks](https://openreview.net/pdf?id=dFbKQaRk15w) *Beatrice Bevilacqua et al.* ICLR 2022. [[code](https://github.com/beabevi/ESAN)] (**ESAN**)
- [Understanding and Extending Subgraph GNNs by Rethinking Their Symmetries](https://openreview.net/pdf?id=sc7bBHAmcN) *Fabrizio Frasca et al.* NIPS 2022. [[code](https://github.com/beabevi/SUN)]
- [Ordered Subgraph Aggregation Networks](https://openreview.net/pdf?id=w0QoqmUT9vJ) *Chendi Qian et al.* NIPS 2022. [[code](https://github.com/Spazierganger/OSAN)] (**OSAN**)

## k-hop Message Passing GNNs
- [MixHop: Higher-Order Graph Convolutional Architectures via Sparsified Neighborhood Mixing](http://proceedings.mlr.press/v97/abu-el-haija19a/abu-el-haija19a.pdf) *Sami Abu-El-Haija. et al.* ICML 2019. [[code](https://github.com/samihaija/mixhop)] (**MixHop**)
- [k-hop graph neural networks](https://www.sciencedirect.com/science/article/pii/S0893608020302495?dgcid=rss_sd_all) *Giannis Nikolentzos et.al.* Neural Networks 2020.[[code](https://github.com/giannisnik/k-hop-gnns)] (**k-hop GNN**)
- [Multi-hop Attention Graph Neural Networks](https://www.ijcai.org/proceedings/2021/0425.pdf) *Guangtao Wang et al.* IJCAI 2021. 
<!-- - [Adaptive Universal Generalized PageRank Graph Neural Network](https://openreview.net/pdf?id=n6jl7fLxrP) *Eli Chien et.al.* ICLR 2021.-->
- [Shortest Path Networks for Graph Property Prediction](https://arxiv.org/pdf/2206.01003.pdf) *Ralph Abboud et al.* 2022.
- [How Powerful are K-hop Message Passing Graph Neural Networks](https://openreview.net/pdf?id=nN3aVRQsxGd) *Jiarui Feng et al.* NIPS 2022. [[code](https://github.com/JiaruiFeng/KP-GNN)](**KP-GNN**)

## WL meets Path/Random Walk
- [Weisfeiler and Leman Go Walking: Random Walk Kernels Revisited](https://openreview.net/pdf?id=Inj9ed0mzQb) *Nils M. Kriege* NIPS 2022. [[code](https://github.com/nlskrg/node_centric_walk_kernels)] (**Node-Centric Walk Kernels**)
- [Redundancy-Free Message Passing for Graph Neural Networks](https://openreview.net/pdf?id=jwVZZzzNKkW) *Rongqin Chen* NIPS 2022. [[code](https://github.com/RongqinChen/Redundancy-Free-Graph-Neural-Networks)] (**RFGNN**)

## Equivariant Graph Networks
- [Invariant and Equivariant Graph Networks](https://arxiv.org/pdf/1812.09902.pdf) *Haggai Maron et al.* ICLR 2019.

## Expressiveness & Efficiency (Complexity) Tradeoff
- [Geodesic Graph Neural Network for Efficient Graph Representation Learning](https://arxiv.org/pdf/2210.02636.pdf) *Lecheng Kong et al.* NIPS 2022. [[code](https://github.com/woodcutter1998/gdgnn)] (**GDGNN**)
- [A Practical, Progressively-Expressive GNN](https://openreview.net/pdf?id=WBv9Z6qpA8x) *Lingxiao Zhao et al.* NIPS 2022. [[code](https://github.com/LingxiaoShawn/KCSetGNN)] (**KCSetGNN**)
- [Exponentially Improving the Complexity of Simulating the Weisfeiler-Lehman Test with Graph Neural Networks](https://openreview.net/pdf?id=AyGJDpN2eR6) *Anders Aamand et al.* NIPS 2022. 
