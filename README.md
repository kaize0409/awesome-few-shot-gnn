## Graph Meta-Learning/Graph Few-Shot Learning [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
The repository contains links primarily to conference and journal publications about graph meta-learning and graph few/zero-shot learning. You are encouraged to contribute to this repo!

Check out our survey: [[IJCAI'22] Few-shot learning on graphs](https://arxiv.org/pdf/2203.09308.pdf)

### Node-level Task
|Name|Paper|Code
|---|---|---|
|Meta-GNN|[[CIKM 2019] Meta-GNN: On Few-shot Node Classification in Graph Meta-learning](https://arxiv.org/pdf/1905.09718.pdf)|[PyTorch](https://github.com/ChengtaiCao/Meta-GNN)
|GPN|[[CIKM 2020] Graph Prototypical Networks for Few-shot Learning on Attributed Networks](https://arxiv.org/pdf/2006.12739.pdf)|[PyTorch](https://github.com/kaize0409/GPN_Graph-Few-shot)
|AMM-GNN|[[CIKM 2020] Graph Few-shot Learning with Attribute Matching](http://www.public.asu.edu/~kding9/pdf/CIKM2020_AMM.pdf)|[N/A]
|G-Meta|[[NeurIPS 2020] Graph Meta Learning via Local Subgraphs](https://arxiv.org/pdf/2006.07889.pdf)|[PyTorch](https://github.com/mims-harvard/G-Meta)
|MetaTNE|[[NuerIPS 2020] Node Classification on Graphs with Few-Shot Novel Labels via Meta Transformed Network Embedding](https://arxiv.org/pdf/2007.02914.pdf)|[PyTorch](https://github.com/llan-ml/MetaTNE)
|M3S|[[AAAI 2020] Multi-Stage Self-Supervised Learning for Graph Convolutional Networks on Graphs with Few Labeled Nodes](https://arxiv.org/pdf/1902.11038.pdf)|[TensorFlow](https://github.com/Junseok0207/M3S_Pytorch)
|RALE|[[AAAI 2021] Relative and Absolute Location Embedding for Few-Shot Node Classification on Graph](https://fangyuan1st.github.io/paper/AAAI21_RALE.pdf)|[TensorFlow](https://github.com/shuaiOKshuai/RALE)
|Meta-GDN|[[WWW 2021] Few-shot Network Anomaly Detection via Cross-network Meta-learning](https://dl.acm.org/doi/pdf/10.1145/3442381.3449922?casa_token=wAEWlJ-gzFoAAAAA:xy36Lut5RVBQhdraG2lfBauW6K-j-TTGfCqc622wdNZ2J1FhaHk3zJ2ezWhy1D3uPy1WXY7gd2Uy)|[PyTorch](https://github.com/kaize0409/Meta-GDN_AnomalyDetection)
|Mixup|[[WWW 2021] Mixup for Node and Graph Classification](https://dl.acm.org/doi/pdf/10.1145/3442381.3449796)|[N/A]
|HAG-Meta|[[WSDM 2022] Graph few-shot class-incremental learning](https://dl.acm.org/doi/abs/10.1145/3488560.3498455)|[PyTorch](https://github.com/Zhen-Tan-dmml/GFCIL)
|AutoGRL|[[IJCNN 2022] Automated Graph Representation Learning for Node Classification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9533811)|[PyTorch](https://github.com/JunweiSUN/AutoGRL)
|MuL-GRN|[[TKDE 2022] MuL-GRN: Multi-Level Graph Relation Network for Few-Shot Node Classification](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9779997)|[N/A]
|Meta-GPS|[[SIGIR 2022] Few-shot Node Classification on Attributed Networks with Graph Meta-learning](https://dl.acm.org/doi/pdf/10.1145/3477495.3531978)|[N/A]
|TENT|[[SIGKDD 2022] Task-Adaptive Few-shot Node Classification](https://arxiv.org/pdf/2206.11972.pdf)|[PyTorch](https://github.com/SongW-SW/TENT)
|KnowPrompt|[[WWW 2022] KnowPrompt: Knowledge-aware Prompt-tuning with Synergistic Optimization for Relation Extraction](https://dl.acm.org/doi/pdf/10.1145/3485447.3511998)|[PyTorch](https://github.com/zjunlp/KnowPrompt)
|IA-FSNC|[[IJCAI 2022] Information Augmentation for Few-shot Node Classifcation](https://www.ijcai.org/proceedings/2022/0500.pdf)|[N/A]
|SGCL|[[ECML 2022] Supervised Graph Contrastive Learning for Few-shot Node Classification](https://arxiv.org/pdf/2203.15936.pdf)|[N/A]
|LADSL|[[Frontiers 2022] Few-shot node classification via local adaptive discriminant structure learning](https://link.springer.com/article/10.1007/s11704-022-1259-6)|[N/A]
|Meta-GIN|[[arXiv 2022] Robust Graph Meta-learning for Weakly-supervised Few-shot Node Classification](https://arxiv.org/pdf/2106.06873.pdf)|[N/A]
|LGLNN|[[NN 2022] LGLNN: Label Guided Graph Learning-Neural Network for few-shot learning](https://www.sciencedirect.com/science/article/pii/S0893608022003033?casa_token=mm5SdWStMbcAAAAA:Z6-LQAvuwIWHtd5LtkxZqTgEbnfwMkrKnIf3-i4q5LxM4M-AXO-6h7wsHleDZFA7NfmHyoU7)|[N/A]
|TLP|[[LOG 2022] Transductive Linear Probing: A Novel Framework for Few-Shot Node Classification](https://openreview.net/pdf?id=dK8vOIBENa3)|[PyTorch](https://github.com/Zhen-Tan-dmml/TLP-FSNC)
|TEG|[[KDD 2023] Task-Equivariant Graph Few-shot Learning](https://arxiv.org/abs/2305.18758)|[PyTorch](https://github.com/sung-won-kim/TEG)
|VNT|[[KDD 2023] Virtual Node Tuning for Few-shot Node Classification](https://arxiv.org/abs/2306.06063)|[N/A]

### Edge-level Task
|Name|Paper|Code
|---|---|---|
|GMatching|[[EMNLP 2018] One-Shot Relational Learning for Knowledge Graphs](https://arxiv.org/pdf/1808.09040.pdf)|[PyTorch](https://github.com/xwhan/One-shot-Relational-Learning)
|FSRL|[[AAAI 2019] Few-Shot Knowledge Graph Completion](http://www.meng-jiang.com/pubs/fsrl-aaai20/fsrl-aaai20-paper.pdf)|[PyTorch](https://github.com/chuxuzhang/AAAI2020_FSRL)
|MetaR|[[EMNLP 2019] Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs](https://aclanthology.org/D19-1431.pdf)|[PyTorch](https://github.com/AnselCmy/MetaR)
|FAAN|[[EMNLP 2020] Adaptive Attentional Network for Few-Shot Knowledge Graph Completion](https://arxiv.org/pdf/2010.09638.pdf)|[PyTorch](https://github.com/JiaweiSheng/FAAN)
|ZSGAN|[[AAAI 2020] Generative Adversarial Zero-Shot Relational Learning for Knowledge Graphs](https://arxiv.org/pdf/2001.02332.pdf)|[PyTorch](https://github.com/Panda0406/Zero-shot-knowledge-graph-relational-learning)
|GEN|[[NeurIPS 2020] Learning to Extrapolate Knowledge: Transductive Few-shot Out-of-Graph Link Prediction](https://arxiv.org/pdf/2006.06648.pdf)|[PyTorch](https://github.com/JinheonBaek/GEN)
|CSR|[[NeurIPS 2022] Few-shot Relational Reasoning via Connection Subgraph Pretraining](https://arxiv.org/pdf/2210.06722.pdf)|[PyTorch](https://github.com/snap-stanford/csr)

### Graph-level Task
|Name|Paper|Code
|---|---|---|
|GFL|[[AAAI 2020] Graph Few-Shot Learning via Knowledge Transfer](http://www.meng-jiang.com/pubs/gfl-aaai20/gfl-aaai20-paper.pdf)|[N/A]
|G-META|[[NuerIPS 2020] Graph Meta Learning via Local Subgraphs](https://proceedings.neurips.cc/paper/2020/file/412604be30f701b1b1e3124c252065e6-Paper.pdf)|[PyTorch](https://github.com/mims-harvard/G-MetaL)
|AS-MAML|[[CIKM 2020] Adaptive-Step Graph Meta-Learner for Few-Shot Graph Classification](https://arxiv.org/pdf/2003.08246.pdf)|[PyTorch](https://github.com/NingMa-AI/AS-MAML)
|Super-class|[[ICLR 2020] Few-shot learning on graphs via super-classes based on graph spectral measures](https://arxiv.org/pdf/2002.12815.pdf)|[PyTorch](https://github.com/chauhanjatin10/GraphsFewShot)
|Meta-MGNN|[[WWW2021] Few-Shot Graph Learning for Molecular Property Prediction](https://dl.acm.org/doi/pdf/10.1145/3442381.3450112?casa_token=_7Jgn7QEFNQAAAAA:2R4orCHFYE8qdIhDeligmCMrMOa1jVyo6Gj8NGZlGhcQ0kGdrTDvhWeHy5rU7hO_Y0B-DEUO-l7s)|[PyTorch](https://github.com/zhichunguo/Meta-MGNN)
|MI-GNN|[[SIGIR 2021] Meta-Inductive Node Classification across Graphs](https://arxiv.org/pdf/2105.06725.pdf)|[PyTorch](https://github.com/WenZhihao666/MI-GNN)
|CuCo|[[IJCAI 2021] CuCo: Graph Representation with Curriculum Contrastive Learning](https://www.ijcai.org/proceedings/2021/0317.pdf)|[PyTorch](https://github.com/BUPT-GAMMA/CuCo)
|GFL-RTG|[[TNNLS 2022] Graph Few-Shot Learning via Restructuring Task Graph](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9791434)|[N/A]
|FAITH|[[IJCAI 2022] FAITH: Few-Shot Graph Classification with Hierarchical Task Graphs](https://arxiv.org/pdf/2205.02435.pdf)|[PyTorch](https://github.com/SongW-SW/FAITH)
|MB-FSGC|[[LoG 2022] Metric Based Few-Shot Graph Classification](https://arxiv.org/abs/2206.03695)|[PyTorch](https://github.com/crisostomi/metric-few-shot-graph)
## Acknowledgement
This page is contributed and maintained by Kaize Ding (kaize.ding@northwestern.edu), Sungwon Kim (swkim@kaist.ac.kr), Donato Crisostomi (crisostomi@di.uniroma1.it), Zhen Tan (ztan36@asu.edu), and Song Wang (sw3wv@virginia.edu).
