# Riemannian Optimization
I am currently working on optimization problems on Riemannian manifolds.
- [Surveys](#Surveys)
- [Feasible Methods](#Feasible_Methods)
- [Infeasible Methods](#infeasible_Methods)
- [Learning Methods](#Learning_Methods)
- [Applications](#Applications)
- [Journals](#Journals)
- [Tools](#Tools)

    
<strong> Last Update: 2023/11/20 </strong>


<a name="Surveys" />

## Surveys
- [2023] An Introduction to Optimization on Smooth Manifolds, Cambridge University Press [[Book](https://www.nicolasboumal.net/book/)] [[Video](https://www.nicolasboumal.net/book/index.html#lectures)]
- [2020] A Brief Introduction to Manifold Optimization, Journal of the Operations Research Society of China [[Paper](https://link.springer.com/article/10.1007/s40305-020-00295-9)]
- [2008] Optimization Algorithms on Matrix Manifolds, Princeton University Press [[Book](https://press.princeton.edu/absil)]


<a name="Feasible_Methods" />

## Feasible Methods
- [2021] Multipliers Correction Methods for Optimization Problems Over the Stiefel Manifold, CSIAM Transactions on Applied Mathematics [[Paper](https://www.global-sci.org/intro/article_detail/csiam-am/19448.html)] [[Matlab](https://stmopt.gitee.io/algorithm_description/ProxOrth_code.html)]
- [2018] A New First-Order Algorithmic Framework for Optimization Problems with Orthogonality Constraints, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/16M1098759)] [[Matlab](https://www.mathworks.com/matlabcentral/fileexchange/71726-foforth)]
- [2015] A Framework of Constraint Preserving Update Schemes for Optimization on Stiefel Manifold, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-014-0816-7)]
- [2013] A Feasible Method for Optimization With Orthogonality Constraints, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-012-0584-1)]
- [2012] Projection-like retractions on matrix manifolds, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/100802529)]
- [2008] Steepest Descent Algorithms for Optimization Under Unitary Matrix Constraint, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/4436033/)]
- [2007] Trust-region methods on Riemannian manifolds, Foundations of Computational Mathematics [[Paper](https://link.springer.com/article/10.1007/s10208-005-0179-9)]
- [2005] Learning Algorithms Utilizing Quasi-Geodesic Flows on the Stiefel Manifold, Neurocomputing [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231205001128)]
- [2002] Optimization Algorithms Exploiting Unitary Constraints, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/984753)]
- [1998] The Geometry of Algorithms With Orthogonality Constraints, SIAM Journal on Matrix Analysis and Applications [[Paper](https://epubs.siam.org/doi/abs/10.1137/S0895479895290954)]


<a name="Infeasible_Methods" />

## Infeasible Methods
- [2023] A Riemannian Smoothing Steepest Descent Method for Non-Lipschitz Optimization on Submanifolds, Mathematics of Operations Research  [[Paper](https://pubsonline.informs.org/doi/abs/10.1287/moor.2022.0286)]
- [2023] An Exact Penalty Approach for Optimization with Nonnegative Orthogonality Constraints, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-022-01794-8)]
- [2023] A Semismooth Newton Based Augmented Lagrangian Method for Nonsmooth Optimization on Matrix Manifolds, Mathematical Programming [[Paper](https://link.springer.com/article/10.1007/s10107-022-01898-1)] [[Matlab](https://github.com/miskcoo/almssn)]
- [2022] Riemannian Stochastic Proximal Gradient Methods for Nonsmooth Optimization Over the Stiefel Manifold, Journal of Machine Learning Research [[Paper](https://dl.acm.org/doi/abs/10.5555/3586589.3586695)]
- [2022] A Manifold Inexact Augmented Lagrangian Method for Nonsmooth Optimization on Riemannian Submanifolds in Euclidean Space, IMA Journal of Numerical Analysis [[Paper](https://academic.oup.com/imajna/article-abstract/43/3/1653/6590238)] [[Matlab](https://github.com/KKDeng/mialm_code_share)]
- [2022] A Class of Smooth Exact Penalty Function Methods for Optimization Problems With Orthogonality Constraints, Optimization Methods and Software [[Paper](https://www.tandfonline.com/doi/abs/10.1080/10556788.2020.1852236?journalCode=goms20)] [[Matlab](https://stmopt.gitee.io/algorithm_description/PenCF_code.html)]
- [2022] Fast and Accurate Optimization on the Orthogonal Manifold Without Retraction, International Conference on Artificial Intelligence and Statistics [[Paper](https://proceedings.mlr.press/v151/ablin22a)]
- [2021] Exact Penalty Function for L2,1 Norm Minimization Over the Stiefel Manifold, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/20M1354313)]  [[Matlab](https://stmopt.gitee.io/algorithm_description/PenCPG_code.html)]
- [2021] Majorization-Minimization on the Stiefel Manifold With Application to Robust Sparse PCA, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9354027)]
- [2021] Clustering by Orthogonal NMF Model and Non-Convex Penalty Optimization, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/9508841)]
- [2020] Proximal Gradient method for Nonsmooth Optimization Over the Stiefel Manifold, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/18M122457X)] [[Matlab](https://github.com/chenshixiang/ManPG)]
- [2019] Parallelizable Algorithms for Optimization Problems With Orthogonality Constraints, SIAM Journal on Scientific Computing [[Paper](https://epubs.siam.org/doi/abs/10.1137/18M1221679)] [[Matlab](https://www.mathworks.com/matlabcentral/fileexchange/71728-pcal)]
- [2019] Structured Quasi-Newton Methods for Optimization With Orthogonality Constraints, SIAM Journal on Scientific Computing [[Paper](https://epubs.siam.org/doi/abs/10.1137/18M121112X)]
- [2018] Adaptive Quadratically Regularized Newton Method for Riemannian Optimization, SIAM Journal on Matrix Analysis and Applications [[Paper](https://epubs.siam.org/doi/abs/10.1137/17M1142478)]
- [2018] A New First-Order Algorithmic Framework for Optimization Problems With Orthogonality Constraints, SIAM Journal on Optimization [[Paper](https://epubs.siam.org/doi/abs/10.1137/16M1098759)] [[Matlab](https://www.mathworks.com/matlabcentral/fileexchange/71726-foforth)]
- [2014] A Splitting Method for Orthogonality Constrained Problems, Journal of Scientific Computing [[Paper](https://link.springer.com/article/10.1007/s10915-013-9740-x)]

  
<a name="Learning_Methods" />

## Learning Methods
- [2023] Learning to Optimize on Riemannian Manifolds, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/9925104)] [[Python](https://github.com/zhigao2017/learningriemannianoptimization)]
- [2021] Orthogonal Deep Neural Networks, IEEE TPAMI [[Paper](https://ieeexplore.ieee.org/abstract/document/8877742)] [[Python](https://github.com/Gorilla-Lab-SCUT/OrthDNNs)]
- [2020] Learning to Optimize on SPD Manifolds, CVPR [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Gao_Learning_to_Optimize_on_SPD_Manifolds_CVPR_2020_paper.html)] [[Python](https://github.com/zhigao2017/Learning-to-optimize-on-SPD-manifolds)]
- [2018] Can We Gain More from Orthogonality Regularizations in Training Deep Networks?  NIPS [[paper](https://proceedings.neurips.cc/paper_files/paper/2018/hash/bf424cb7b0dea050a42b9739eb261a3a-Abstract.html)]  [[Python](https://github.com/VITA-Group/Orthogonality-in-CNNs)]


<a name="Applications" />

## Applications
- [2023] A Communication-Efficient and Privacy-Aware Distributed Algorithm for Sparse PCA, Computational Optimization and Applications [[Paper](https://link.springer.com/article/10.1007/s10589-023-00481-4)] [[C](http://lsec.cc.ac.cn/~liuxin/Solvers/DSSAL1.zip)]
- [2023] Federated PCA on Grassmann Manifold for Anomaly Detection in IoT Networks, IEEE INFOCOM [[Paper](https://ieeexplore.ieee.org/abstract/document/10229026)] [[Python](https://github.com/dual-grp/FedPCA_Abnormal_Detection)]
- [2023] Discriminative subspace learning via optimization on Riemannian manifold, Pattern Recognition [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320323001504)] [[Matlab](https://github.com/ncclabsustech/MODA-algorithm)]
- [2022] Trace Lasso Regularization for Adaptive Sparse Canonical Correlation Analysis via Manifold Optimization Approach, IEEE TKDE  [[Paper](https://ieeexplore.ieee.org/document/9187560)] [[Matlab](https://github.com/KKDeng/ASCCA)]
- [2022] FAST-PCA: A Fast and Exact Algorithm for Distributed Principal Component Analysis, IEEE TSP [[Paper](https://ieeexplore.ieee.org/abstract/document/10012289)]
- [2021] Communication-Efficient Distributed Covariance Sketch, With Application to Distributed PCA, Journal of Machine Learning Research [[Paper](https://dl.acm.org/doi/abs/10.5555/3546258.3546338)]
- [2021] Distributed Principal Component Analysis with Limited Communication, NIPS [[Paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/1680e9fa7b4dd5d62ece800239bb53bd-Abstract.html)] [[Matlab](https://github.com/IST-DASLab/QRGD)]
- [2020] Communication-Efficient Distributed PCA by Riemannian Optimization, ICML [[Paper](https://proceedings.mlr.press/v119/huang20e.html)] [[Matlab](https://github.com/IST-DASLab/QRGD)]
- [2020] An Alternating Manifold Proximal Gradient Method for Sparse Principal Component Analysis and Sparse Canonical Correlation Analysis, INFORMS Journal on Optimization [[Paper](https://pubsonline.informs.org/doi/abs/10.1287/ijoo.2019.0032)] [[Matlab](https://github.com/chenshixiang)]
- [2019] Solving Partial Least Squares Regression via Manifold Optimization Approaches, IEEE TNNLS [[Paper](https://ieeexplore.ieee.org/abstract/document/8408735)] [[Matlab](https://github.com/Haoran2014/PLSR_RM)]


<a name="Journals" />

## Journals
- IEEE Transactions on Pattern Analysis and Machine Intelligence  [[Link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34)]
- IEEE Transactions on Signal Processing [[Link](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=78)]
- Journal of Scientific Computing  [[Link](https://www.springer.com/journal/10915)]

<a name="Tools" />

## Tools
- Manopt: A Matlab Toolbox for Optimization on Manifolds  [[Link](https://www.manopt.org/)]
- STOP: A Toolbox for Stiefel Manifold Optimization [[Link](https://stmopt.gitee.io/)]
