# Dijkstras Algorithm
Given a weighted digraph and a source node, find the minimum weight of of paths from the source node to every other node.
* Weighted digraph $G=(V,E)$, where $V$ is a set of vertices and $E$ is a set of $(v,w)$ directed edges.
* Source node $s\in V$
* Positive weight function on edges $wt:E\rightarrow \mathbb{R}_0^+$
**Output**: A function of the minimum weight path from $s$ to every other node in the graph
$$\forall v\in V, \delta(v)=\begin{dcases}
	\text{min weight of any path from s to v}\\
	\infty, \text{if no path exists from s to v}
\end{dcases}$$
