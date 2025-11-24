# Numerical Linear Algebra

This course focused on numerical methods for solving linear algebra problems, combining theoretical foundations with practical implementation. The projects emphasized both understanding the mathematics behind the algorithms and implementing efficient numerical solutions.


## Assignments / Projects

### 1. [Project 1: Direct Methods in Optimization with Constraints](./pr1_NLA_direct_methods.ipynb)

Implemented direct methods for constrained optimization by solving the KKT system. Tasks included writing routines for step-size substeps, implementing the full algorithm for test problems, and comparing computation times for different problem sizes.  
- **Challenges:** This was a particularly difficult project. I did not reach all the expected results but gained a strong understanding of KKT systems and numerical linear algebra techniques.   

**Report:** [Direct Methods in Optimization with Constraints Report](./PR1_NLA_direct_methods.pdf) 


### 2. [Project 2: SVD Applications](./pr2_nla_SVD.ipynb)
Explored applications of Singular Value Decomposition (SVD) in three areas:  
1. **Least Squares Problems:** Solved for the minimum-norm solution of linear systems using SVD and compared with QR-based solutions.  
2. **Graphics Compression:** Created low-rank approximations of images to compress `.jpeg` files while retaining as much information as possible.  
3. **Principal Component Analysis (PCA):** Performed dimensionality reduction, extracting principal components and variance from datasets.  
  
**Report:** [SVD Applications Report](./PR2_NLA_SVD_Applications.pdf) 


### 3. [Project 3: PageRank Implementations](./pr3_nla_pagerank.ipynb)
Implemented two versions of the PageRank algorithm:  
1. Using the power method with the full matrix representation of the network.  
2. Using an iterative method that avoids storing the full matrix, leveraging sparse data structures.  

**Report:** [PageRank Implementations Report](./PR3_NLA_PageRank.pdf) 


