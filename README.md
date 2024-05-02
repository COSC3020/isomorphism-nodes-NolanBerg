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

A bijection is a function that is one-to-one (injective) and onto (surjective):

For $( f: V_1 \rightarrow V_2 )$ to be a bijection, the sizes of $( V_1 )$ and $( V_2 )$ must be equal because:

- If $( |V_1| > |V_2| )$, then $( f )$ cannot be surjective 

- If $( |V_1| < |V_2| )$, then $( f )$ cannot be injective

Proof by Contradiction

Two graphs $( A )$ and $( B )$, with $( A = (V_A, E_A) )$ and $( B = (V_B, E_B) )$, do not have same number of nodes

Claim: $( A )$ and $( B )$ cannot be isomorphic.

Proof:

- Suppose there is a bijection $( f: V_A \rightarrow V_B )$.

- By definition of a bijection, $( |V_A| )$ equals $( |V_B| )$ since elements of $( V_A )$ must map to every element of $( V_B )$.

- But this contradicts our assumption that $( |V_A| \neq |V_B| )$.

- So no such bijection $( f )$ can exist if $( |V_A| \neq |V_B| )$.
