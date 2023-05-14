O desafio pode ser encontrado em [Desafio @mathgurl](https://www.youtube.com/watch?v=N2Lr1NVLGVw)


#### **Modelagem Matemática**

$$
Min \quad \sum_{i \in I} \sum_{j \in J} y_{i,j} \\
S.t: \quad y_{ij} = \sum_{k \in K} x_{ijk} \quad \forall i \in I, j \in J \quad \quad (1) \\

\quad \quad \sum_{k \in K} x_{ijk} = 1 \quad \forall i \in I, j \in J \qquad \qquad (2) \\

\sum_{(\hat{i},\hat{j}) \in \{(\hat{i},\hat{j}) \mid \hat{i} \in I, \hat{j} \in J, \, |\hat{i} - i| + |\hat{j} - j| \leq k\}} x_{\hat{i}\hat{j}k} \leq M(1 - x_{ijk}) + x_{ijk} \quad \forall i \in I, j \in J, k \in K \quad (3) \\

x_{i,j,k} \in {0,1} \quad \forall i \in I, j \in J, k \in K \qquad \quad(4)  \\

1 \leq y_{i,j} \leq 8 \quad \forall i \in I, j \in J \qquad \quad \quad \quad \quad (5)
$$