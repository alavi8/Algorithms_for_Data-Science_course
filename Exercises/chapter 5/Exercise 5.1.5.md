
# Exercise 5.1.5 :<br>
## Show by induction on n that if the second, third, and fourth components of a vector v are equal, and M is the transition matrix of Example 5.1, then the second, third, and fourth components are also equal in Mnv for any n ≥ 0.



### solution :
 
 we have :
 
 M=
$\begin{bmatrix}
0&1/2&1&0\\
1/3&0&0&1/2\\
1/3&0&0&1/2\\
1/3&1/2&0&0\\
\end{bmatrix}$ , v0 = 
$\begin{bmatrix}
a\\
b\\
b\\
b\\
\end{bmatrix}$ 
<br>


 step 1:(t=1)<br>
 
 
 $\begin{equation*}
\ {M}^1
\end{equation*}$v=$\begin{bmatrix}
3b/2=a\\
(2a+3b)/6=b\\
(2a+3b)/6=b\\
(2a+3b)/6=b\\
\end{bmatrix}$ 
<br>

 step 2:(t=2)<br>
 
 
$\begin{equation*}
\ {M}^2
\end{equation*}$v=$\begin{bmatrix}
(2a+3b)/4=a\\
(2a+9b)/12=b\\
(2a+9b)/12=b\\
(2a+9b)/12=b\\
\end{bmatrix}$ 
<br>



step n-1:(t=n-1)<br>



$\begin{equation*}
\ {M}^{(n-1)}
\end{equation*}$v=$\begin{bmatrix}
a\\
b\\
b\\
b\\
\end{bmatrix}$ 
<br>



step n:(t=n)<br>



$\begin{equation*}
\ {M}^{n}
\end{equation*}$v=$\begin{bmatrix}
a\\
b\\
b\\
b\\
\end{bmatrix}$ 
<br>


```python

```
