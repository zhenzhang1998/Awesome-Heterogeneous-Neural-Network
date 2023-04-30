# Awesome Heterogeneous Neural Network
🎉🎉🎉 A List of Heterogeneous Neural Network Pappers 🎉🎉🎉
![Awesome](awesome.png)

## Pre-Learning Materials
  - [Graph Structure Knowledge](https://www.bilibili.com/video/BV16v4y1b7x7/?spm_id_from=333.788&vd_source=d496a4b7477de878a88c60b654607663)
  - [GCN Teaching Video](https://www.bilibili.com/video/BV1Hs4y157Ls/?spm_id_from=333.788&vd_source=d496a4b7477de878a88c60b654607663)
  - [Tool: PyG](https://pytorch-geometric.readthedocs.io/en/latest/index.html)
  - [Tool: DGL](https://docs.dgl.ai/en/latest/)
  - [Tool: Torch.Sparse](https://pytorch.org/docs/stable/sparse.html?highlight=torch+sparse#module-torch.sparse)

## Figure out the concepts
  - what the means of Heterogeneous Nerual Network ? 
  - what the means of meta-path ?
  - what the means of neighborhood of specific meta-path ?
  - what the means of neighbor-sample ?
  - what the means of n-hops ?
  - why the number of n-hops is small (< 3 usually) ?
  - what the advantages of metapath-based methods ?
  - what the advantages of neighbor-sample-based methods ?
  
## Useful Third-Tools
  - [gtrick](https://github.com/sangyx/gtrick) : Common Trick for GNN Training.
  - [GNN](src/model.py) : Common GNN implementation with PyG

## Heterogeneous Nerual Network Papers
  - [Inductive Representation Learning on Large Graphs](https://export.arxiv.org/pdf/1706.02216.pdf) : GraphSAGE(2017 NeurIPS)
  - [Modeling Relational Data with Graph Convolutional Networks](https://arxiv.org/pdf/1703.06103v4.pdf) : RGCN(2018 The Semantic Web)
  - [Heterogeneous Graph Neural Network](https://dl.acm.org/doi/pdf/10.1145/3292500.3330961) : HetGNN(2019 KDD)
  - [Graph Transformer Networks](https://export.arxiv.org/pdf/1911.06455.pdf) : Graph Transformer Networks(2019 NeurIPS)
  - [Representation Learning for Attributed Multiplex Heterogeneous Network](http://export.arxiv.org/pdf/1905.01669) : GATNE(2019 KDD) 
  - [Heterogeneous Graph Attention Network](https://arxiv.org/pdf/1903.07293v2.pdf) : HAN(2019 WWW)
  - [Heterogeneous Graph Transformer](https://arxiv.org/pdf/2003.01332.pdf) : HGT(2020 WWW)
  - [Heterogeneous Graph Neural Network via Attribute Completion](https://dl.acm.org/doi/abs/10.1145/3442381.3449914) : HGNN-AC(2021 WWW)
  - [Multiplex Heterogeneous Graph Convolutional Network](https://arxiv.org/pdf/2208.06129) : MHGCN(2022 KDD)
  - [Meta-node: A Concise Approach to Effectively Learn Complex Relationships in Heterogeneous Graphs](https://arxiv.org/abs/2210.14480) : Meta-node(2022)
  - [Simple and Efficient Heterogeneous Graph Neural Network](http://arxiv.org/abs/2207.02547) : SeHGNN(2023 AAAI)
  - updating...

## Heterogeneous Nerual Network & Social Recommendation Papers
  - [Hierarchical representation learning for bipartite graphs](https://www.ijcai.org/Proceedings/2019/0398.pdf) : Bi-HGG(2019 IJCAI)
  - [Hierarchical Bipartite Graph Neural Networks: Towards Large-Scale E-commerce Applications](https://ieeexplore.ieee.org/document/9101846) : HiGNN(2020 ICDE)
  - [DiffNet++: A Neural Influence and Interest Diffusion Network for Social Recommendation](https://arxiv.org/abs/2002.00844) : DiffNet++(2020 TKDE)
  - [A Graph Neural Network Framework for Social Recommendations](https://ieeexplore.ieee.org/document/9139346) : GraphRec+(2022 TKDE)
  - [A Survey of Graph Neural Networks for Social Recommender Systems](https://arxiv.org/pdf/2212.04481) : Graph-Social-Recommender-Systems Survey(2022)
  - [Disentangled Contrastive Learning for Social Recommendation](https://arxiv.org/abs/2208.08723v1): DcRec(2022 CIKM)
  - [Large-scale Personalized Video Game Recommendation via Social-aware Contextualized Graph Neural Network](https://arxiv.org/pdf/2202.03392.pdf) : SCGRec(2022 WWW)
  - [Inhomogeneous Social Recommendation with Hypergraph Convolutional Networks](https://arxiv.org/pdf/2111.03344.pdf) : SHGCN(2022 ICDE)
  - updating
