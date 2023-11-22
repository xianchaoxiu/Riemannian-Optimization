# Distributed Optimization
I am currently working on distributed/decentralized optimization problems on Riemannian manifolds.
- [Surveys](#Surveys)
- [Distributed Optimization](#Distributed_Optimization)
- [Federated Learning](#Federated_Learning)
- [Applications](#Applications)
- [Journals](#Journals)
- [Tools](#Tools)

    
<strong> Last Update: 2023/11/20 </strong>


<a name="Surveys" />

## Surveys
- [2023] Communication-Efficient Distributed Learning: An Overview, IEEE JSAC  [[Paper](https://ieeexplore.ieee.org/document/10038471)]
- [2022] Federated Learning: A Signal Processing Perspective, IEEE SPM  [[Paper](https://ieeexplore.ieee.org/abstract/document/9770266)]
- [2021] A Comprehensive Survey of Privacy-preserving Federated Learning: A Taxonomy, Review, and Future Directions, ACM Computing Surveys [[Paper](https://dl.acm.org/doi/abs/10.1145/3460427)]
- [2021] A Survey on Federated Learning: The Journey From Centralized to Distributed On-Site Learning and Beyond, IEEE JIOT [[Paper](https://ieeexplore.ieee.org/abstract/document/9220780)]
- [2020] First-order and Stochastic Optimization Methods for Machine Learning, Springer [[Book](https://link.springer.com/content/pdf/10.1007/978-3-030-39568-1.pdf)]
- [2020] Secure, Privacy-Preserving and Federated Machine Learning in Medical Imaging, Nature Machine Intelligence [[Paper](https://www.nature.com/articles/s42256-020-0186-1)]
- [2020] Federated Learning: Challenges, Methods, and Future Directions, IEEE SPM [[Paper](https://ieeexplore.ieee.org/abstract/document/9084352)]
- [2020] A Survey on Distributed Machine Learning, ACM Computing Surveys [[Paper](https://dl.acm.org/doi/abs/10.1145/3377454)]
- [2019] A Survey of Distributed Optimization, Annual Reviews in Control [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1367578819300082)]
- [2019] Federated Machine Learning: Concept and Applications, ACM Transactions on Intelligent Systems and Technology  [[Paper](https://dl.acm.org/doi/abs/10.1145/3298981)]
- [2018] A Review of Distributed Algorithms for Principal Component Analysis, P IEEE [[Paper](https://ieeexplore.ieee.org/abstract/document/8425655)]
- [2011] Distributed Optimization and Statistical Learning via the Alternating Direction Method of Multipliers, Foundations and Trends in Machine Learning [[Paper](https://www.nowpublishers.com/article/Details/MAL-016)]



<a name="Distributed_Optimization" />

## Distributed Optimization

### Euclidean Spaces
- [2022] Distributed Adaptive Newton Methods with Global Superlinear Convergence, Automatica [[Paper](https://www.sciencedirect.com/science/article/pii/S0005109821006865)]
- [2022] Achieving Geometric Convergence for Distributed Optimization with Barzilai-Borwein Step Sizes, Science China Information Sciences  [[Paper](http://scis.scichina.com/en/2022/149204.pdf)]
- [2021] On Distributed Nonconvex Optimization: Projected Subgradient Method for Weakly Convex Problems in Networks, IEEE TAC [[Paper](https://ieeexplore.ieee.org/abstract/document/9345428)]
- [2021] A Penalty Alternating Direction Method of Multipliers for Convex Composite Optimization Over Decentralized Networks, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9466405)]
- [2017] Non-Convex Distributed Optimization, IEEE TAC [[Paper](https://ieeexplore.ieee.org/abstract/document/7807315)]
- [2016] Distributed Compressive Sensing: A Deep Learning Approach, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/7457684)]  [[Matlab](https://github.com/hamidpalangi/Distributed-Compressive-Sensing-A-Deep-Learning-Approach)] 
- [2016] On the Convergence of Decentralized Gradient Descent, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/130943170)]
- [2015] EXTRA: An Exact First-Order Algorithm for Decentralized Consensus Optimization, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/14096668X)]
- [2010] Distributed Stochastic Subgradient Projection Algorithms for Convex Optimization, Journal of Optimization Theory and Applications [[Paper](https://link.springer.com/article/10.1007/s10957-010-9737-7)]
  


### Riemannian Spaces
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, Computational Optimization and Applications [[Paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[C](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2022] Decentralized Optimization Over the Stiefel Manifold by an Approximate Augmented Lagrangian Function, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9798866)] [[Python](http://lsec.cc.ac.cn/~liuxin/Solvers/DEST.zip)]
- [2022] FAST-PCA: A Fast and Exact Algorithm for Distributed Principal Component Analysis, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/10012289)]
- [2021] Decentralized Riemannian gradient descent on the Stiefel manifold, ICML [[Paper](https://proceedings.mlr.press/v139/chen21g.html)] [[Python](https://github.com/chenshixiang/Decentralized_Riemannian_gradient_descent_on_Stiefel_manifold)]
- [2021] Communication-Efficient Distributed Covariance Sketch, With Application to Distributed PCA, Journal of Machine Learning Research [[Paper](https://dl.acm.org/doi/abs/10.5555/3546258.3546338)]
- [2021] Distributed Principal Component Analysis with Limited Communication, NIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/1680e9fa7b4dd5d62ece800239bb53bd-Abstract.html)] [[Matlab](https://github.com/IST-DASLab/QRGD)]
- [2020] Communication-Efficient Distributed PCA by Riemannian Optimization, ICML [[Paper](https://proceedings.mlr.press/v119/huang20e.html)] [[Matlab](https://github.com/IST-DASLab/QRGD)]



<a name="Federated_Learning" />

## Federated Learning
- [2023] Federated Learning via Inexact ADMM, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/10040221)] [[Matlab](https://github.com/ShenglongZhou/FedADMM)]
- [2023] FedGiA: An Efficient Hybrid Algorithm for Federated Learning, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/10106001)] [[Matlab](https://github.com/ShenglongZhou/FedGiA)]
- [2022] Federated Learning Meets Multi-Objective Optimization, IEEE TNSE [[Paper](https://ieeexplore.ieee.org/abstract/document/9762229)]



<a name="Applications" />

## Applications

- [2023] Federated PCA on Grassmann Manifold for Anomaly Detection in IoT Networks, IEEE INFOCOM [[Paper](https://ieeexplore.ieee.org/abstract/document/10229026)] [[Python](https://github.com/dual-grp/FedPCA_Abnormal_Detection)]
- [2022] A New Look and Convergence Rate of Federated Multitask Learning With Laplacian Regularization, IEEE TNNLS [[Paper](https://ieeexplore.ieee.org/abstract/document/9975151)] [[Python](https://github.com/CharlieDinh/FedU_FMTL)]
- [2021] Federated Learning Over Wireless Networks: Convergence Analysis and Resource Allocation, IEEE/ACM TNET [[Paper](https://ieeexplore.ieee.org/abstract/document/9261995)] [[Python](https://github.com/CharlieDinh/FEDL_pytorch)]




<a name="Journals" />

## Journals
- IEEE Transactions on Pattern Analysis and Machine Intelligence  [[Link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)]
- IEEE Transactions on Automatic Control  [[Link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9)]
- IEEE Transactions on Signal Processing [[Link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=78)]


<a name="Tools" />

## Tools
- ADMM: Alternating Direction Method of Multipliers  [[Link](https://web.stanford.edu/~boyd/papers/admm_distr_stats.html)]
