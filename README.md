[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

Sources: Used google for this assignment

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Objective

Show that graphs $( G_1 )$ and $( G_2 )$ cannot be isomorphic if they do not have the same number of nodes. We will prove this by contradiction.

A bijection is a function that is both one-to-one (injective) and onto (surjective):

- Injective: No two distinct elements in $( V_1 )$ map to the same element in $( V_2 )$.

- Surjective: Every element in $( V_2 )$ has a pre-image in $( V_1 )$.

For $( f: V_1 \rightarrow V_2 )$ to be a bijection, the sizes of $( V_1 )$ and $( V_2 )$ must be equal because:

- If $( |V_1| > |V_2| )$, then $( f )$ cannot be surjective 

- If $( |V_1| < |V_2| )$, then $( f )$ cannot be injective
