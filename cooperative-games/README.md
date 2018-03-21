Here, I'll experiment with algorithms for solution concepts in cooperative game theory. Cooperative games are remarkably versatile,
showing up in any applications involving fair division, whether splitting a taxi fare or allocating resources on a network. To deal with these problems, we use a variety of solution concepts, each of which satisfies different fairness axioms (e.g. emphasizing equity over equality, or vice versa).

A major problem is that many solution concepts are computationally hard. For example, the Shapley value formula involves factorials,
so its complexity increases very fast as the number of players gets larger. However, we can recast the Shapley value as a problem 
involving weighted graphs, for which many efficient algorithms already exist.

Another response is to develop variations on standard solution concepts, designed to be more  algorithmically tractable. 
Nonetheless, these new solution concepts are seldom used in the economics literature.

Therefore, this project consists of the following parts:
<ul>
<li> Develop algorithms to compute solution concepts, both classical and from CS</li>
<li> Gauge the complexity of these algorithms, try to develop polynomial-time solutions</li>
<li> Replicate applied papers using solution concepts from the CS literature</li>
</ul>

The literature on cooperative games in CS tends to use advanced computational tools, but fairly shallow economic theory.
This project aims in part to find more <i>economically</i> interesting applications for CS-based methods.

&nbsp;

## Updates

18.02.12: Added working paper – “The Shapley Value: An Extremely Short Introduction” (<a href="https://github.com/gjoncas/Computational-Economics/blob/master/cooperative-games/shapley%20value.pdf">2015</a>)
