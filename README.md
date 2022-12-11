![hooke_jeeves_search](https://user-images.githubusercontent.com/45152248/206932134-fcdd8517-17e2-45ee-9e83-28fdcad6a0dd.gif)
# hooke_jeeves

Hooke Jeeves Search is a very effective gradient-free #optimization algorithm. It traverses the search space based on evaluations at small steps in each design dimension. If no improvements are found, the step size is decreased. Until the step size is sufficiently small, the process occurs. It requires 2n function evaluations for a n-dimensional problem.

Speedups can be achieved by turning the method into opportunistic: as soon as an evaluation improves the current best design, it is accepted. In the plot, the opportunistic variant is marked as an X and the traditional implementation is marked as a dot. The objective function is a 2D sphere.
