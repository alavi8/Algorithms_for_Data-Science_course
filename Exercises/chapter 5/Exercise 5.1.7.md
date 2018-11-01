
# Exercise 5.1.7 :
## Repeat Exercise 5.1.6 for the tree of dead ends suggested by Fig. 5.10. That is, there is a single node with a self-loop, which is also the root of a complete binary tree of n levels.<br>





### solution :<br> 
We call the vertices from the left, respectively :<br>
step 1 :(1)<br>
step 2:(Respectively from above) (2),(3)<br>
step 3 : (Respectively from above) (21),(22),(31),(32)<br>
,.......

Remove all of the dead ends recursively .<br>
 
thus we get :


$\begin{equation*}
\ {v}_0
\end{equation*}$ =[1] , M=[1] 


PageRank of (1) = 1;<br>
PageRank of (2) = PageRank of (3) = 1/3×1 ;<br>
PageRank of (21) = PageRank of (22) = PageRank of (31) = PageRank of (32) = 1/3×1/2×1 ;<br>
and ......























```python

```
