
# Exercise 5.1.3 :<br>
## Suppose the Web consists of a clique (set of nodes with all possible arcs from one to another) of n nodes and a single additional node that is the successor of each of the n nodes in the clique. Figure 5.8 shows this graph for the case n = 4. Determine the PageRank of each page, as a function of n and β.



### solution :


for graph we have:

v0 : 
$\begin{bmatrix}
1/5\\
1/5\\
1/5\\
1/5\\
1/5\\
\end{bmatrix}$ 
and  M:
$\begin{bmatrix}
0&1/4&1/4&1/4&0\\
1/4&0&1/4&1/4&1/4\\
1/4&1/4&0&1/4&0\\
1/4&1/4&1/4&0&0\\
1/4&1/4&1/4&1/4&0\\
\end{bmatrix}$
<br>


Thus, the equationfor the iteration becomes :

$\begin{equation*}
\ v'
\end{equation*}$ =βMv+(1-β)e/n


$\begin{equation*}
\ v'
\end{equation*}$ =β
$\begin{bmatrix}
0&1/4&1/4&1/4&0\\
1/4&0&1/4&1/4&1/4\\
1/4&1/4&0&1/4&0\\
1/4&1/4&1/4&0&0\\
1/4&1/4&1/4&1/4&0\\
\end{bmatrix}$
 v + (1-β)  $\begin{bmatrix}
1\\
1\\
1\\
\end{bmatrix}$ 


```python

```
