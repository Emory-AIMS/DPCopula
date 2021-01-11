# DPCopula
DPCopula is a differentially private data synthesization technique using Copula functions for
multi-dimensional data. The core of the method is to
compute a differentially private copula function to sample synthetic data. Copula functions are used to
describe the dependence between multivariate random vectors and to build the multivariate joint distribution
using one-dimensional marginal distributions. The parameters of the copula
functions are estimated with differential privacy via maximum likelihood
estimation and Kendall’s τ estimation. Experiments
using both real datasets and synthetic datasets demonstrate
that DPCopula generates highly accurate synthetic multidimensional data with significantly better utility than stateof-the-art techniques.

Reference

Haoran Li, Li Xiong, Xiaoqian Jiang. Differentially Private Synthesization of Multi-Dimensional Data using Copula Functions. In EDBT 2014
http://www.mathcs.emory.edu/aims/pub/li14edbt.pdf
