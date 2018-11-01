
# Exercise 5.3.1 :
## Compute the topic-sensitive PageRank for the graph of Fig.5.15, assuming the teleport set is:
## (a) A only.

## (b) A and C.




### solution : <br>

#### a)

 we have:<br>
 S={A}<br>
 $\begin{equation*}
\ {e}_s
\end{equation*}$ = $\begin{bmatrix}
1\\
0\\
0\\
0\\
\end{bmatrix}$ 

M=
$\begin{bmatrix}
0&1/2&1&0\\
1/3&0&0&1/2\\
1/3&0&0&1/2\\
1/3&1/2&0&0\\
\end{bmatrix}$

<br>


v0 : 
$\begin{bmatrix}
1\\
0\\
0\\
0\\
\end{bmatrix}$ 



The topic-sensitive PageRank for S is the limit of the iteration :

$\begin{equation*}
\ v'
\end{equation*}$ =βMv+(1-β) $\begin{equation*}
\ {e}_s
\end{equation*}$ /|S|

Thus, the equationfor the iteration becomes :


$\begin{equation*}
\ v'
\end{equation*}$=
$\begin{bmatrix}
0&2/5&4/5&0\\
4/15&0&0&2/5\\
4/15&0&0&2/5\\
4/15&2/5&0&0\\
\end{bmatrix}$ v +$\begin{bmatrix}
0.2\\
0\\
0\\
0\\
\end{bmatrix}$

The first few iterations of this equation:

$\begin{bmatrix}
1\\
0\\
0\\
0\\
\end{bmatrix}$   ,    $\begin{bmatrix}
1/5\\
4/15\\
4/15\\
4/15\\
\end{bmatrix}$   ,    $\begin{bmatrix}
13/25\\
4/25\\
4/25\\
4/25\\
\end{bmatrix}$   ,    $\begin{bmatrix}
49/125\\
76/375\\
76/375\\
76/375\\
\end{bmatrix}$   ,    ,....



#### b)

 we have:<br>
 S={A,C}<br>
 $\begin{equation*}
\ {e}_s
\end{equation*}$ = $\begin{bmatrix}
1\\
0\\
1\\
0\\
\end{bmatrix}$ 

M=
$\begin{bmatrix}
0&1/2&1&0\\
1/3&0&0&1/2\\
1/3&0&0&1/2\\
1/3&1/2&0&0\\
\end{bmatrix}$

<br>


v0 : 
$\begin{bmatrix}
1/2\\
0\\
1/2\\
0\\
\end{bmatrix}$ 



The topic-sensitive PageRank for S is the limit of the iteration :

$\begin{equation*}
\ v'
\end{equation*}$ =βMv+(1-β) $\begin{equation*}
\ {e}_s
\end{equation*}$ /|S|

Thus, the equationfor the iteration becomes :


$\begin{equation*}
\ v'
\end{equation*}$=
$\begin{bmatrix}
0&2/5&4/5&0\\
4/15&0&0&2/5\\
4/15&0&0&2/5\\
4/15&2/5&0&0\\
\end{bmatrix}$ v +$\begin{bmatrix}
1/10\\
0\\
1/10\\
0\\
\end{bmatrix}$

The first few iterations of this equation:

$\begin{bmatrix}
1/2\\
0\\
1/2\\
0\\
\end{bmatrix}$   ,    $\begin{bmatrix}
1/2\\
2/15\\
7/30\\
2/15\\
\end{bmatrix}$   ,   $\begin{bmatrix}
17/50\\
14/75\\
43/150\\
14/75\\
\end{bmatrix}$   ,   $\begin{bmatrix}
101/250\\
62/375\\
199/750\\
62/375\\
\end{bmatrix}$   ,   ,....












```python

```
