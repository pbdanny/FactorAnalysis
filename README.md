# FactorAnalysis

__Correlation matrix.__
observed correlation matrix. 
reproduced correlation matrix. 
residual correlation matrix. 

__Rotation factor.__
1)  orthogonal.  
    loading matrix : correlation between observed variable vs factor.
2)  oblique.  
    factor correlation matrix : correlation between factor vs factor.
    structure matrix : correlation variable vs factor.
    pattern matrix : correlation each factors and each variable.

factor-score coefficient matrix.

PCA product component. : observed variable ->(caused) components.
FA produce factor. : factor ->(caused) observed variable.

PCA all varience in observed variable analized.
FA shared varience is analized.

Step to compute FA/PCA.

1)  Find eigenvalue, eigenvector (Diagonalization) of Covarience matrix (or Correlation matrix). Eigenvalues = re-package of correlation (covarience) matrix.
2)  Correlation matrix = Eigen Vactor x Eigen Value x Eigen Vactor'. 
    Correlation matrix = Eigen Vactor x sqrt(Eigen Value) x sqrt(Eigen Value) x Eigen Vactor'. 
    Eigen Vector x sqrt(Eigen Value) -> Factor Loading.
    Correlation matrix = Factor loading x Factor loading'.
3)  Factor Loading = correlation between factor and variable, First column = First factor , each rows = correlation with each variables
