# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

----------------------------------------------------------------------------------------

Assuming that $A = (V_1, E_1)$ and $B = (V_2, E_2)$ are two graphs with the same number of nodes and are both completely connected.

Then  $\exists f$ such that $f: A \rightarrow B$ then the first node of A would map to the first node of B, then the second to the second, and so on until all nodes have been mapped.  Since they both have the same number of nodes it would be a one-to-one mapping as there would always be a node of A that maps to a node of B.  

Next, looking at edges, since both graphs are complete we will go about it the same way, first edge of A corresponds to the first edge of B, so on and so forth until we're out of edges, then we will see that since both graphs have the same amount of nodes they will have the same number of edges.  Meaning then that if two graphs have the same number of vertices and are both completely connected, they *must* be isomorphic

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
