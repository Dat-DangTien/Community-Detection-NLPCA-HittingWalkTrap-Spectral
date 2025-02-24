# Community-Detection-NLPCA-HittingWalkTrap-Spectral
This project codes the algorithms presented in the paper "Community detection in directed graphs using stationary distribution and hitting times methods" (https://link.springer.com/article/10.1007/s13278-023-01080-1).

The algorithms include: the spectral method algorithm for optimizing the modularity function $Q_p$, Hitting times WalkTrap and Normalized Laplacian PCA (NL-PCA).

# Explain structure of folder

The folder `Code` includes 2 Jupyter notebook files:
1. `AutoComparison_all_algs_directed_graph.ipynb`: Compares NL-PCA algorithms, hitting walktrap, with other spectral algorithms such as oPCA, Dscore, rPCA, and directed Louvain.
2. `fully_Q_proposed_direct_graph.ipynb`: Compares a spectral algorithm for optimizing $Q_p$ on a random graph, then evaluates it against the labels of those graphs.

The folder `dataset` includes directed graph datasets.

The folder `images_results` includes images after running code.

The folder `graph_saved` includes random graph data.

# How to run
You can run simply by running all cells in both two notebooks.

