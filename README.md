# FactorAnalysis

Correlation matrix.

observed correlation matrix
reproduced correlation matrix
residual correlation matrix
Rotation factor.

orthogonal.
loading matrix : correlation between observed variable vs factor.
oblique.
factor correlation matrix : correlation between factor vs factor.
structure matrix : correlation variable vs factor.
pattern matrix : correlation each factors and each variable.
factor-score coefficient matrix.

PCA product component. : observed variable ->(caused) components.
FA produce factor. : factor ->(caused) observed variable.

PCA all varience in observed variable analized.
FA shared varience is analized.

Step to compute FA/PCA.

Find eigenvalue, eigenvector (Diagonalization) of Covarience matrix (or Correlation matrix). Gigenvalues = re-package of correlation (covarience) matrix.
Correlation matrix = Eigen Vactor x Eigen Value x Eigen Vactor'. Correlation matrix = Eigen Vactor x sqrt(Eigen Value) x sqrt(Eigen Value) x Eigen Vactor'. Eigen Vector x sqrt(Eigen Value) -> Factor Loading.
Correlation matrix = Factor loading x Factor loading'.
Factor Loading = correlation between factor and variable, First column = First factor , each rows = correlation with each variables
