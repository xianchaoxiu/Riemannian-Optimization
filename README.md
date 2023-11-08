# Distributed Optimization

We now focus on distributed/decentralized optimization problems over manifold constraints.
- [Surveys](#Surveys)
- [Manifold Learning](#Manifold_Learning)
- [Distributed Learning](#Distributed_Learning)
- [Federated Learning](#Federated_Learning)
- [Applications](#Applications)
- [Journals](#Journals)
  
<strong> Last Update: 2023/11/8 </strong>


<a name="Surveys" />

## Surveys

- [2023] An Introduction to Optimization on Smooth Manifolds, Cambridge University Press [[book](https://www.nicolasboumal.net/book/)]
- [2022] CDOpt: A Python Package for a Class of Riemannian Optimization, arXiv  [[paper](https://arxiv.org/abs/2212.02698)] [[code](https://cdopt.github.io/md_files/intro.html)]
- [2021] A Comprehensive Survey of Privacy-preserving Federated Learning: A Taxonomy, Review, and Future Directions, ACM Computing Surveys [[paper](https://dl.acm.org/doi/abs/10.1145/3460427)]
- [2020] Secure, Privacy-Preserving and Federated Machine Learning in Medical Imaging, Nature Machine Intelligence [[paper](https://www.nature.com/articles/s42256-020-0186-1)] 
- [2019] Federated Machine Learning: Concept and Applications, ACM Transactions on Intelligent Systems and Technology  [[paper](https://dl.acm.org/doi/abs/10.1145/3298981)]
- [2020] A Brief Introduction to Manifold Optimization, Journal of the Operations Research Society of China [[paper](https://link.springer.com/article/10.1007/s40305-020-00295-9)]
- [2014]  Manopt, a Matlab Toolbox for Optimization on Manifolds, Journal of Machine Learning Research  [[paper](https://www.jmlr.org/papers/volume15/boumal14a/boumal14a.pdf)] [[code](https://www.manopt.org/)]
- [2008] Optimization algorithms on matrix manifolds, Princeton University Press [[book](https://press.princeton.edu/absil)]
  


  
<a name="Manifold_Learning" />

## Manifold Learning

### Feasible Algorithms
- [2021] Multipliers Correction Methods for Optimization Problems Over the Stiefel Manifold, CSIAM Transactions on Applied Mathematics [[paper](https://www.global-sci.org/intro/article_detail/csiam-am/19448.html)] [[code](https://stmopt.gitee.io/algorithm_description/ProxOrth_code.html)]
- [2018] A New First-Order Algorithmic Framework for Optimization Problems with Orthogonality Constraints, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/16M1098759)] [[code](https://www.mathworks.com/matlabcentral/fileexchange/71726-foforth)]
- [2015] A Framework of Constraint Preserving Update Schemes for Optimization on Stiefel Manifold, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-014-0816-7)]
- [2013] A Feasible Method for Optimization With Orthogonality Constraints, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-012-0584-1)]
- [2012] Projection-like retractions on matrix manifolds, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/100802529)]
- [2008] Steepest Descent Algorithms for Optimization Under Unitary Matrix Constraint, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/4436033/)]
- [2007] Trust-region methods on Riemannian manifolds, Foundations of Computational Mathematics [[paper](https://link.springer.com/article/10.1007/s10208-005-0179-9)]
- [2005] Learning Algorithms Utilizing Quasi-Geodesic Flows on the Stiefel Manifold, Neurocomputing [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231205001128)]
- [2002] Optimization Algorithms Exploiting Unitary Constraints, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/984753)]
- [1998] The Geometry of Algorithms With Orthogonality Constraints, SIAM Journal on Matrix Analysis and Applications [[paper](https://epubs.siam.org/doi/abs/10.1137/S0895479895290954)]


### Infeasible Algorithms
- [2023] A Riemannian Smoothing Steepest Descent Method for Non-Lipschitz Optimization on Submanifolds, Mathematics of Operations Research  [[paper](https://pubsonline.informs.org/doi/abs/10.1287/moor.2022.0286)]
- [2023] An Exact Penalty Approach for Optimization with Nonnegative Orthogonality Constraints, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-022-01794-8)]
- [2023] A Semismooth Newton Based Augmented Lagrangian Method for Nonsmooth Optimization on Matrix Manifolds, Mathematical Programming [[paper](https://link.springer.com/article/10.1007/s10107-022-01898-1)] [[code](https://github.com/miskcoo/almssn)]
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, Computational Optimization and Applications [[paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2022] Riemannian Stochastic Proximal Gradient Methods for Nonsmooth Optimization Over the Stiefel Manifold, Journal of Machine Learning Research [[paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586695)]
- [2022] A Manifold Inexact Augmented Lagrangian Method for Nonsmooth Optimization on Riemannian Submanifolds in Euclidean Space, IMA Journal of Numerical Analysis  [[paper](https://academic.oup.com/imajna/article-abstract/43/3/1653/6590238)] [[code](https://github.com/KKDeng/mialm_code_share)]
- [2022] A Class of Smooth Exact Penalty Function Methods for Optimization Problems With Orthogonality Constraints, Optimization Methods and Software [[paper](https://www.tandfonline.com/doi/abs/10.1080/10556788.2020.1852236?journalCode=goms20)] [[code](https://stmopt.gitee.io/algorithm_description/PenCF_code.html)]
- [2022] Decentralized Optimization Over the Stiefel Manifold by an Approximate Augmented Lagrangian Function, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9798866)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DEST.zip)]
- [2022] Fast and Accurate Optimization on the Orthogonal Manifold Without Retraction, International Conference on Artificial Intelligence and Statistics [[paper](https://proceedings.mlr.press/v151/ablin22a)]
- [2021] Exact Penalty Function for L2,1 Norm Minimization Over the Stiefel Manifold, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/20M1354313)]  [[code](https://stmopt.gitee.io/algorithm_description/PenCPG_code.html)]
- [2021] Majorization-Minimization on the Stiefel Manifold With Application to Robust Sparse PCA, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9354027)]
- [2021] Clustering by Orthogonal NMF Model and Non-Convex Penalty Optimization, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9508841)]
- [2020] Proximal Gradient method for Nonsmooth Optimization Over the Stiefel Manifold, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/18M122457X)] [[code](https://github.com/chenshixiang/ManPG)]
- [2019] Parallelizable Algorithms for Optimization Problems With Orthogonality Constraints, SIAM Journal on Scientific Computing [[paper](https://epubs.siam.org/doi/abs/10.1137/18M1221679)] [[code](https://www.mathworks.com/matlabcentral/fileexchange/71728-pcal)]
- [2019] Structured Quasi-Newton Methods for Optimization With Orthogonality Constraints, SIAM Journal on Scientific Computing [[paper](https://epubs.siam.org/doi/abs/10.1137/18M121112X)]
- [2018] Adaptive Quadratically Regularized Newton Method for Riemannian Optimization, SIAM Journal on Matrix Analysis and Applications [[paper](https://epubs.siam.org/doi/abs/10.1137/17M1142478)]
- [2018] A New First-Order Algorithmic Framework for Optimization Problems With Orthogonality Constraints, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/16M1098759)] [[code](https://epubs.siam.org/doi/abs/10.1137/16M1098759)]
- [2014] A Splitting Method for Orthogonality Constrained Problems, Journal of Scientific Computing [[paper](https://link.springer.com/article/10.1007/s10915-013-9740-x)]
  


### Learning Algorithms
- [2023] Learning to Optimize on Riemannian Manifolds, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/9925104)] [[code](https://github.com/zhigao2017/learningriemannianoptimization)]
- [2021] Orthogonal Deep Neural Networks, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/8877742)]
- [2020] Learning to Optimize on SPD Manifolds, CVPR [[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Gao_Learning_to_Optimize_on_SPD_Manifolds_CVPR_2020_paper.html)] [[code](https://github.com/zhigao2017/Learning-to-optimize-on-SPD-manifolds)]
- [2018] Can We Gain More from Orthogonality Regularizations in Training Deep Networks?  NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2018/hash/bf424cb7b0dea050a42b9739eb261a3a-Abstract.html)]



<a name="Distributed_Learning" />

## Distributed Learning
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, Computational Optimization and Applications [[paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2022] Decentralized Optimization Over the Stiefel Manifold by an Approximate Augmented Lagrangian Function, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9798866)] [[code](http://lsec.cc.ac.cn/~liuxin/Solvers/DEST.zip)]
- [2022] Distributed Adaptive Newton Methods with Global Superlinear Convergence, Automatica [[paper](https://www.sciencedirect.com/science/article/pii/S0005109821006865)]
- [2022] Achieving Geometric Convergence for Distributed Optimization with Barzilai-Borwein Step Sizes, Science China Information Sciences  [[paper](http://scis.scichina.com/en/2022/149204.pdf)]
- [2021] On Distributed Nonconvex Optimization: Projected Subgradient Method for Weakly Convex Problems in Networks, IEEE TAC [[paper](https://ieeexplore.ieee.org/abstract/document/9345428)]
- [2021] Decentralized Riemannian gradient descent on the Stiefel manifold, ICML [[paper](https://proceedings.mlr.press/v139/chen21g.html)] [[code](https://github.com/chenshixiang/Decentralized_Riemannian_gradient_descent_on_Stiefel_manifold)]
- [2021] A Penalty Alternating Direction Method of Multipliers for Convex Composite Optimization Over Decentralized Networks, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/9466405)] 
- [2016] On the Convergence of Decentralized Gradient Descent, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/130943170)]
- [2015] EXTRA: An Exact First-Order Algorithm for Decentralized Consensus Optimization, SIAM Journal on Optimization [[paper](https://epubs.siam.org/doi/abs/10.1137/14096668X)]
- [2010] Distributed Stochastic Subgradient Projection Algorithms for Convex Optimization, Journal of Optimization Theory and Applications [[paper](https://link.springer.com/article/10.1007/s10957-010-9737-7)]
- [2022] FAST-PCA: A Fast and Exact Algorithm for Distributed Principal Component Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10012289)]
- [2021] Communication-Efficient Distributed Covariance Sketch, With Application to Distributed PCA, Journal of Machine Learning Research [[paper](https://dl.acm.org/doi/abs/10.5555/3546258.3546338)]
- [2021] Distributed Principal Component Analysis with Limited Communication, NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/1680e9fa7b4dd5d62ece800239bb53bd-Abstract.html)] [[code](https://github.com/IST-DASLab/QRGD)]
- [2020] Communication-Efficient Distributed PCA by Riemannian Optimization, ICML [[paper](https://proceedings.mlr.press/v119/huang20e.html)]
- [2018] A Review of Distributed Algorithms for Principal Component Analysis, P IEEE [[paper](https://ieeexplore.ieee.org/abstract/document/8425655)]



<a name="Federated_Learning" />

## Federated Learning
- [2023] Federated Learning via Inexact ADMM, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10040221)] [[code](https://github.com/ShenglongZhou/FedADMM)]
- [2023] FedGiA: An Efficient Hybrid Algorithm for Federated Learning, IEEE TPAMI [[paper](https://ieeexplore.ieee.org/abstract/document/10106001)] [[code](https://github.com/ShenglongZhou/FedGiA)]
- [2023] Communication-Efficient Federated Linear and Deep Generalized Canonical Correlation Analysis, IEEE TSP [[paper](https://ieeexplore.ieee.org/abstract/document/10099447)] [[code](https://github.com/XiaoFuLab/federated_max_var_gcca)]




<a name="Applications" />
  
## Applications
- [2023] Discriminative subspace learning via optimization on Riemannian manifold, Pattern Recognition [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320323001504)] [[code](https://github.com/ncclabsustech/MODA-algorithm)]
- [2022] Trace Lasso Regularization for Adaptive Sparse Canonical Correlation Analysis via Manifold Optimization Approach, IEEE TKDE  [[paper](https://ieeexplore.ieee.org/document/9187560)] [[code](https://github.com/KKDeng/ASCCA)]
- [2022] Learning Inter- and Intra-Manifolds for Matrix Factorization-Based Multi-Aspect Data Clustering, IEEE TKDE  [[paper](https://link.springer.com/article/10.1007/s40305-022-00449-x)] [[code](https://github.com/khanhluongds/Multi-viewClustering_DiMMA)]
- [2021] Deep Manifold Learning for Dynamic MR Imaging, IEEE TCI [[paper](https://ieeexplore.ieee.org/abstract/document/9632354)] [[code](https://github.com/Keziwen/Manifold_Net)]
- [2020] An Alternating Manifold Proximal Gradient Method for Sparse Principal Component Analysis and Sparse Canonical Correlation Analysis, INFORMS Journal on Optimization [[paper](https://pubsonline.informs.org/doi/abs/10.1287/ijoo.2019.0032)] [[code](https://github.com/chenshixiang)]
- [2019] Solving Partial Least Squares Regression via Manifold Optimization Approaches, IEEE TNNLS [[paper](https://ieeexplore.ieee.org/abstract/document/8408735)] [[code](https://github.com/Haoran2014/PLSR_RM)]


<a name="Journals" />

## Journals
- IEEE Transactions on Pattern Analysis and Machine Intelligence  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)]
- IEEE Transactions on Neural Networks and Learning Systems  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385)]
- IEEE Journal of Selected Topics in Signal Processing  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4200690)]
- IEEE Transactions on Automatic Control  [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=9)]
- IEEE Transactions on Signal Processing [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=78)]
- IEEE Signal Processing Letters [[link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=97)]

