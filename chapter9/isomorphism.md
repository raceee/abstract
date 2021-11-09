#chapter9

#### Definition of Isomorphism

Two [[group]] $(G, \circ)$ and $(H, \circ)$ are isomorphic if there exists a bijective map $\phi : G\rightarrow H$ such that the group operations is preserved; that is $$\phi (a * b) = \phi (a) \circ\phi (b)$$ for all $a$ and $b$ in $G$. If $G$ is isomorphic to $H$, we write $G \cong H$. The map $\phi$ is called an isomorphism.

---

#### Statements of Isomorphisms
Let $\phi : G\rightarrow H$ be an isomorphism of two groups. Then the following statements are true:
* $\phi^{-1}: H\rightarrow G$ is an isomorphism
* $\vert G\vert = \vert H\vert$
* If $G$ is [[abelian]], then $H$ is [[abelian]]
* If $G$ is [[cyclic]], then $H$ is [[cyclic]]
* If $G$ has a [[subgroup]] of order $n$, then $H$ has a [[subgroup]] of order $n$

---

##### examples
1. $$(\mathbb{R}, + )\cong (\mathbb{R}^+, * )$$ by $$\phi(x) = e^x$$ because it preserves operation $$\phi (x+y) = e^{x+y} = e^x e^y = \phi (x) \phi (y)$$
2. $$(\mathbb{R} , + ) \ncong (\mathbb{R}^* , *)$$By contradiction: Suppose there is an isomorphism $\phi : \mathbb{R}\rightarrow\mathbb{R}^*$. There is an $a\in\mathbb{R}$ such that $\phi (a) = -1$. Then $a = \frac{a}{2} + \frac{a}{2}$. But, $-1 = \phi (a) = \phi (\frac{a}{2} + \frac{a}{2}) = \phi(\frac{a}{2}) *\phi(\frac{a}{2}) = \phi (\frac{a}{2})^2$.