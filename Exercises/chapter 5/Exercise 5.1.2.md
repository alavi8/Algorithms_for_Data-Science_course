

```python

```

# Exercise 5.1.2 :

## Compute the PageRank of each page in Fig. 5.7, assuming β = 0.8.<br>




### solution : <br>



for the graph we have vector v0 and Matrix M :<br>

v0 : 
$\begin{bmatrix}
1/3\\
1/3\\
1/3\\
\end{bmatrix}$ 
and  M:
$\begin{bmatrix}
1/3&1/2&0\\
1/3&0&1/2\\
1/3&1/2&1/2\\
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
1/3&1/2&0\\
1/3&0&1/2\\
1/3&1/2&1/2\\
\end{bmatrix}$
 v + $\begin{bmatrix}
1/15\\
1/15\\
1/15\\
\end{bmatrix}$ 

Here are the first few iterations:


$\begin{bmatrix}
1/3\\
1/3\\
1/3\\
\end{bmatrix}$

$\begin{bmatrix}
13/45\\
13/45\\
19/45\\
\end{bmatrix}$

$\begin{bmatrix}
7/27\\
211/675\\
289/675\\
\end{bmatrix}$<br>
* 
* 
* 
<br>

$\begin{bmatrix}
0.2\\
0.3\\
0.4\\
\end{bmatrix}$

we now know that the PageRank of a is 0.20 & b is 0.31 & c is 0.40 .


```python

```
