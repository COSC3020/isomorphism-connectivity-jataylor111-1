# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

-------------------------------------------------------------------------------

We talked about this a little bit when I asked about the definition of isomorphism all those weeks ago.  But, we can do this via counterexample.

If we have two graphs $A = (V_1, E_1)$ and $B = (V_2, E_2)$, that both only have one node and no edges then they are both isomorphic.

If both only have one node then there exists a function $f: V_1 \rightarrow V_2$ that must be both one-to-one and onto since there is only one node in each.  Also since there are no edges in either then 0 edges corresponds to 0 edges.

And so both $A$ and $B$ are isomorphic which means that two graphs do not necessarily need to be completely connected to be isomorphic.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice
