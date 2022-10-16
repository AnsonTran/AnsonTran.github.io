# Greedy Algorithms
Our goal with optimization problems is to take in some input, some constraints on those inputs, and find a greedy picking strategy that always produces an output that is:
1. **Feasible** - Satifies the given constraints defined in the problem
2. **Optimized** - Optimizes (maximizes or minimizes) a desired criterion (the objective function)

Greedy algorithms do so by always choosing the best solution "myopically". This approach works when we can:
* Building a solution incrementally
* Each step produces a partial solution, and we can extend it ot a more complete solution greedily, choosing the immediate best step
* Each step is irreversible, meaning we cannot backtrack

## Greedy Stays Ahead
We can use the 'Greedy Stays Ahead' argument in order to prove the optimality of greedy algorithms.
1. Let $A$ be a solution given by following the greedy choice of the algorithm
2. Let $A^*$ be an optimal solution, such that $A$ and $A^*$ are the same up to some k-th element, where they differ
3. Show that by swapping the k-th value of $A^*$ with the k-th value of $A$, we maintain the optimality of $A^*$
4. Therefore, the greedy strategy of $A$ produces a solution that is optimal

There can be multiple optimal solutions, and if we can show that optimality is maintained at the k-th step, the same argument applies for any other step where $A$ and $A^*$ differs.

## Promising Set Technique
The promising set technique maintains an invariant:
1. Let $A$ be the solution produced by the greedy algorithm
2. At the end of iteration $t$, let $A_t$ be the set contained in $A$ at the end of iteration $t$. $A_t$ is contained in **some** optimal set $A^*$

Consider iteration $t+1$:
1. $A_{t+1} = A_t$, in which case $A_t$ is optimal
2. $A_{t+1}=A_t \cup j$, we must prove that $A_{t+1}$ is in some $A^*$
