
# Exercise 5.1.6 :<br>
## Suppose we recursively eliminate dead ends from the graph, solve the remaining graph, and estimate the PageRank for the dead-end pages as described in Section 5.1.4. Suppose the graph is a chain of dead ends, headed by a node with a self-loop, as suggested in Fig. 5.9. What would be the PageRank assigned to each of the nodes?



### solution :

We call the vertices from the left, respectively (1),(2),(3),........,(n)

Remove all of the dead ends recursively:
 
(1),(2),(3),........,(n-1)<br>
 ....
 
(1),(2),(3),(4)<br>
(1),(2),(3)<br>
(1),(2)<br>
(1)<br>

thus we get :


$\begin{equation*}
\ {v}_0
\end{equation*}$ =[1] , M=[1] 

PageRank of (1) = 1;<br>
PageRank of (2) = (1/2)×1;<br>
PageRank of (3) = PageRank of (2) = 1/2;<br>
PageRank of (4) = PageRank of (3) = 1/2;<br>
,......

PageRank of (n) = PageRank of (n-1) = 1/2;<br>







```python

```
