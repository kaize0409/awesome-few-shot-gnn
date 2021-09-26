### [Few-shot and Zero-shot Learning](#content)

1. **Few-Shot Learning with Graph Neural Networks.** ICLR 2018. [paper](https://arxiv.org/pdf/1711.04043.pdf)

    *Victor Garcia, Joan Bruna.* 

1. **Prototype Propagation Networks (PPN) for Weakly-supervised Few-shot Learning on Category Graph.** IJCAI 2019. [paper](https://arxiv.org/pdf/1905.04042.pdf)

    *Lu Liu, Tianyi Zhou, Guodong Long, Jing Jiang, Lina Yao, Chengqi Zhang.*

1. **Edge-labeling Graph Neural Network for Few-shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1905.01436.pdf)

    *Jongmin Kim, Taesup Kim, Sungwoong Kim, Chang D. Yoo.*
    
1. **Generating Classification Weights with GNN Denoising Autoencoders for Few-Shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1905.01102.pdf)

    *Spyros Gidaris, Nikos Komodakis.*
    
1. **Zero-shot Recognition via Semantic Embeddings and Knowledge Graphs.** CVPR 2018. [paper](https://arxiv.org/pdf/1803.08035.pdf)

    *Xiaolong Wang, Yufei Ye, Abhinav Gupta.* 

1. **Rethinking Knowledge Graph Propagation for Zero-Shot Learning.** CVPR 2019. [paper](https://arxiv.org/pdf/1805.11724.pdf)

    *Michael Kampffmeyer, Yinbo Chen, Xiaodan Liang, Hao Wang, Yujia Zhang, Eric P. Xing.* 

1. **Multi-Label Zero-Shot Learning with Structured Knowledge Graphs.** CVPR 2018. [paper](https://arxiv.org/pdf/1711.06526.pdf)

    *Chung-Wei Lee, Wei Fang, Chih-Kuan Yeh, Yu-Chiang Frank Wang.* 

1. **Learning to Propagate for Graph Meta-Learning.** NeurIPS 2019. [paper](http://papers.nips.cc/paper/by-source-2019-610)

	*LU LIU, Tianyi Zhou, Guodong Long, Jing Jiang, Chengqi Zhang.*

1. **Attribute Propagation Network for Graph Zero-­shot Learning.** AAAI 2020. [paper]()

	*LU LIU, Tianyi Zhou, Guodong Long, Jing Jiang, Chengqi Zhang.*

1. **Graph Few-­‐shot Learning via Knowledge Transfer.** AAAI 2020. [paper](https://arxiv.org/abs/1910.03053)

	*Huaxiu Yao, Chuxu Zhang, Ying WEI, Meng Jiang, Suhang Wang, Junzhou Huang, Nitesh Chawla, Zhenhui Li.*

1. **FEW-SHOT LEARNING ON GRAPHS VIA SUPER-CLASSES BASED ON GRAPH SPECTRAL MEASURES.** ICLR 2020. [paper](https://openreview.net/pdf?id=Bkeeca4Kvr)

	*Jatin Chauhan, Deepak Nathani, Manohar Kaul.*

1. **Learning to Extrapolate Knowledge: Transductive Few-shot Out-of-Graph Link Prediction.** NeurIPS 2020. [paper](https://arxiv.org/abs/2006.06648)

	*Jinheon Baek, Dong Bok Lee, Sung Ju Hwang.*

1. **Graph Meta Learning via Local Subgraphs.** NeurIPS 2020. [paper](https://papers.nips.cc/paper/2020/hash/412604be30f701b1b1e3124c252065e6-Abstract.html)

    *Kexin Huang, Marinka Zitnik.*
    
    
## Graph Few/Zero-shot Learning

### Node-level Tasks

|Task|Paper|Code|Data
|---|---|---|---|
|Propensity Score Matching|[[ICLR 2018] Few-Shot Learning with Graph Neural Networks](https://arxiv.org/pdf/1711.04043.pdf)|[Python](https://github.com/akelleh/causality/tree/master/causality/estimation)|
|Nonparametric Regression Adjustment|   |[Python](https://github.com/akelleh/causality)|
|BNN, BLR|[Johansson, Fredrik, Uri Shalit, and David Sontag. "Learning representations for counterfactual inference." In International Conference on Machine Learning, pp. 3020-3029. 2016.](http://www.jmlr.org/proceedings/papers/v48/johansson16.pdf)|[Python](https://github.com/oddrose/cfrnet)|
|TARNet, Counterfactual Regression|[Shalit, Uri, Fredrik D. Johansson, and David Sontag. "Estimating individual treatment effect: generalization bounds and algorithms." arXiv preprint arXiv:1606.03976 (2016).](https://arxiv.org/pdf/1606.03976)|[Python](https://github.com/oddrose/cfrnet)|
|Causal Effect VAE|[Louizos, Christos, Uri Shalit, Joris M. Mooij, David Sontag, Richard Zemel, and Max Welling. "Causal effect inference with deep latent-variable models." In Advances in Neural Information Processing Systems, pp. 6446-6456. 2017.](http://papers.nips.cc/paper/7223-causal-effect-inference-with-deep-latent-variable-models.pdf)|[Python](https://github.com/AMLab-Amsterdam/CEVAE)|
|SITE|[Yao, Liuyi, Sheng Li, Yaliang Li, Mengdi Huai, Jing Gao, and Aidong Zhang. "Representation Learning for Treatment Effect Estimation from Observational Data." In Advances in Neural Information Processing Systems, pp. 2638-2648. 2018.](https://papers.nips.cc/paper/7529-representation-learning-for-treatment-effect-estimation-from-observational-data.pdf)|[Python](https://github.com/Osier-Yi/SITE)|
|X-learner|[Künzel, Sören R., Jasjeet S. Sekhon, Peter J. Bickel, and Bin Yu. "Metalearners for estimating heterogeneous treatment effects using machine learning." Proceedings of the National Academy of Sciences 116, no. 10 (2019): 4156-4165.](https://www.pnas.org/content/pnas/early/2019/02/14/1804597116.full.pdf)|[R](https://github.com/soerenkuenzel/hte)[R](https://github.com/xnie/rlearner/blob/master/R/xlearner.R)|
|Causal Forest|[Wager, Stefan, and Susan Athey. "Estimation and inference of heterogeneous treatment effects using random forests." Journal of the American Statistical Association just-accepted (2017).](https://www.tandfonline.com/doi/pdf/10.1080/01621459.2017.1319839)|[R](https://github.com/grf-labs/grf) [Python](https://github.com/kjung/scikit-learn)|
|Causal MARS, Causal Boosting, Pollinated Transformed Outcome Forests|[S. Powers et al., “Some methods for heterogeneous treatment effect estimation in high-dimensions,” 2017.](https://arxiv.org/pdf/1707.00102.pdf)|[R](https://github.com/grf-labs/grf) [R](https://github.com/saberpowers/causalLearning)|
|Bayesian Additive Regression Trees (BART)|[Hill, Jennifer L. "Bayesian nonparametric modeling for causal inference." Journal of Computational and Graphical Statistics 20, no. 1 (2011): 217-240.](https://www.tandfonline.com/doi/pdf/10.1198/jcgs.2010.08162)|[Python](https://github.com/JakeColtman/bartpy)|
|GANITE|[Yoon, Jinsung, James Jordon, and Mihaela van der Schaar. "GANITE: Estimation of Individualized Treatment Effects using Generative Adversarial Nets." (2018).](https://openreview.net/forum?id=ByKWUeWA-)|[Python](https://github.com/jsyoon0823/GANITE)|
|Perfect Match|[Schwab, Patrick, Lorenz Linhardt, and Walter Karlen. "Perfect match: A simple method for learning representations for counterfactual inference with neural networks." arXiv preprint arXiv:1810.00656 (2018)](https://arxiv.org/pdf/1810.00656)|[Python](https://github.com/d909b/perfect_match)|
|Dragonnet|[Adapting Neural Networks for the Estimation of Treatment Effects](https://arxiv.org/abs/1906.02120)|[Python](https://github.com/claudiashi57/dragonnet)|
|Active Learning for Decision-Making from Imbalanced Observational Data|[Active Learning for Decision-Making from Imbalanced Observational Data](https://arxiv.org/abs/1904.05268)|NA|
|ABCEI|[Adversarial Balancing-based Representation Learning for Causal Effect Inference with Observational Data](https://arxiv.org/pdf/1904.13335.pdf)|NA|
|NSGP (Non-stationary Gaussian Process Prior)|[Alaa, Ahmed, and Mihaela Schaar. "Limits of estimating heterogeneous treatment effects: Guidelines for practical algorithm design." In International Conference on Machine Learning, pp. 129-138. 2018.](http://proceedings.mlr.press/v80/alaa18a/alaa18a.pdf)|NA|
|CMGP (Causal Multi-task Gaussian Processes)|[Alaa, Ahmed M., and Mihaela van der Schaar. "Bayesian inference of individualized treatment effects using multi-task gaussian processes." In Advances in Neural Information Processing Systems, pp. 3424-3432. 2017.](https://papers.nips.cc/paper/6934-bayesian-inference-of-individualized-treatment-effects-using-multi-task-gaussian-processes.pdf)|NA|
|BNR-NNM(balanced and nonlinear representations-nearest neighbor matching)|[Li, Sheng, and Yun Fu. "Matching on balanced nonlinear representations for treatment effects estimation." In Advances in Neural Information Processing Systems, pp. 929-939. 2017.](http://papers.nips.cc/paper/6694-matching-on-balanced-nonlinear-representations-for-treatment-effects-estimation.pdf)|NA|
|Deep Counterfactual Networks (Propensity Dropout)|[Alaa, Ahmed M., Michael Weisz, and Mihaela van der Schaar. "Deep counterfactual networks with propensity-dropout." arXiv preprint arXiv:1706.05966 (2017)](https://arxiv.org/pdf/1706.05966)|NA|
||[Kallus, Nathan, Xiaojie Mao, and Angela Zhou. "Interval Estimation of Individual-Level Causal Effects Under Unobserved Confounding." In The 22nd International Conference on Artificial Intelligence and Statistics, pp. 2281-2290. 2019.](https://arxiv.org/abs/1810.02894)|NA|
|Multiple Responses in Uplift Models|[Weiss, Sam. Estimating and Visualizing Business Tradeoffs in Uplift Models](https://medium.com/building-ibotta/estimating-and-visualizing-business-tradeoffs-in-uplift-models-80ff845a5698) |[Python](https://github.com/Ibotta/mr_uplift)|
