
# Exercise 5.5.2 : 
## Suppose our graph is a chain of n nodes, as was suggested by Fig. 5.9. Compute the hubs and authorities vectors, as a function of n.



solution :

we have :<br>
$\begin{equation*}
\ {L}
\end{equation*}$ =
$\begin{bmatrix}
1&1&0&0&\ldots &0\\
0&0&1&0&\ldots &0\\
0&0&0&1&\ldots&0\\
\vdots&\vdots&\vdots&\vdots&\ddots& \vdots\\
0&0&0&0&\ldots&1\\
\end{bmatrix}$


$\begin{equation*}
\ {L}^T
\end{equation*}$ =$\begin{bmatrix}
1&0&0&0&\ldots &0\\
1&0&0&0&\ldots &0\\
0&1&0&0&\ldots&0\\
\vdots&\vdots&\vdots&\vdots&\ddots& \vdots\\
0&0&0&0&\ldots&1\\
\end{bmatrix}$

$\begin{equation*}
\ {h}
\end{equation*}$ =$\begin{bmatrix}
1\\
1\\
1\\
\vdots\\
1\\
\end{bmatrix}$


$\begin{equation*}
\ {L}^T
\end{equation*}$$\begin{equation*}
\ {h}
\end{equation*}$ = $\begin{bmatrix}
1\\
1\\
1\\
\vdots\\
1\\
\end{bmatrix}$ = $\begin{equation*}
\ {a}
\end{equation*}$



$\begin{equation*}
\ {L}
\end{equation*}$$\begin{equation*}
\ {a}
\end{equation*}$ = $\begin{bmatrix}
2\\
1\\
1\\
\vdots\\
1\\
\end{bmatrix}$ <br>
$\begin{equation*}
\ {h}
\end{equation*}$ =$\begin{bmatrix}
1\\
1/2\\
1/2\\
\vdots\\
1/2\\
\end{bmatrix}$


$\begin{equation*}
\ {L}^T
\end{equation*}$$\begin{equation*}
\ {h}
\end{equation*}$ = $\begin{bmatrix}
1\\
1\\
1/2\\
\vdots\\
1/2\\
\end{bmatrix}$ = $\begin{equation*}
\ {a}
\end{equation*}$



$\begin{equation*}
\ {L}
\end{equation*}$$\begin{equation*}
\ {a}
\end{equation*}$ = $\begin{bmatrix}
2\\
1/2\\
1/2\\
\vdots\\
1/2\\
\end{bmatrix}$ <br>
$\begin{equation*}
\ {h}
\end{equation*}$ =$\begin{bmatrix}
1\\
1/4\\
1/4\\
\vdots\\
1/4\\
\end{bmatrix}$



$\begin{equation*}
\ {L}^T
\end{equation*}$$\begin{equation*}
\ {h}
\end{equation*}$ = $\begin{bmatrix}
1\\
1\\
1/4\\
\vdots\\
1/4\\
\end{bmatrix}$ = $\begin{equation*}
\ {a}
\end{equation*}$


$\begin{equation*}
\ {L}
\end{equation*}$$\begin{equation*}
\ {a}
\end{equation*}$ = $\begin{bmatrix}
2\\
1/4\\
1/4\\
\vdots\\
1/4\\
\end{bmatrix}$ <br>
$\begin{equation*}
\ {h}
\end{equation*}$ =$\begin{bmatrix}
1\\
1/8\\
1/8\\
\vdots\\
1/8\\
\end{bmatrix}$

$\begin{equation*}
\ {L}^T
\end{equation*}$$\begin{equation*}
\ {h}
\end{equation*}$ = $\begin{bmatrix}
1\\
1\\
1/8\\
\vdots\\
1/8\\
\end{bmatrix}$ = $\begin{equation*}
\ {a}
\end{equation*}$

* 
* 
* <br>

$\begin{equation*}
\ {h}
\end{equation*}$=$\begin{bmatrix}
1\\
1/{2}^n\\
1/{2}^n\\
\vdots\\
1/{2}^n\\
\end{bmatrix}$

,


$\begin{equation*}
\ {a}
\end{equation*}$=$\begin{bmatrix}
1\\
1\\
1/{2}^n\\
\vdots\\
1/{2}^n\\
\end{bmatrix}$





```python

```
