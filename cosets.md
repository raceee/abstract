Let G be a group and H a [[subgroup]] of G. Define a left coset of H with representative $g\in G$ to be the set $$gH = \{ gh: h\in H\}$$

Right coset is similar:
$$Hg = \{ hg: h\in H\}$$
If left and right cosets coincide or if it is clear from the context to which type of coset that we are referring, we will use the word *coset* without specificy left or right.

## Example
Let a group be ($\mathbb{Z}_8, +_8$) has the following subgroups:
$$H_1 = \{0\}$$$$H_2 = \{\mathbb{Z}_8 \}$$$$H_3 = \{ 0,2,3,6\}$$$$H_4 = \{0, 4\}$$

Cosets of $H_4$:
$$0 + H_4 = \{0, 4\} = 4 + H_4$$
$$1 + H_4 = \{1, 5\}$$
They go up to $3 + H_4$

Cosets of a subgroup are disjoint


## Example
Let $G = S_3$ be a [[Symmetric Group]], and let a [[subgroup]] $H = \{(1), (12)\}$

If the element $g = (1)$ then $gH = Hg = H$ are the cosets

If we allow $g = (1,2)$ then $$gH = H = Hg$$

If $g = (1,3)$ then $$gH = \{(13),(123)\}$$ $$Hg = \{(13), (132)\}$$

* Either two cosets are equal or they are disjoint
* If left and right cosets are equal then the operations is [[abelian]]

## Lemma
Let $H\leq G$ and $g_1 , g_2 \in G$. Then $g_1 H = g_2 H$ iff $g_{1}^{-1}g_2 \in H$.

Proof
($\rightarrow$) Suppose $g_1 H = g_2 H$. Then $g_1 h_1 = g_2 h_2$ for some $h_1, h_2 \in H$ then $h_1 h_{2}^{-1} = g_{1}^{-1}g_2 \in H$

($\leftarrow$) Suppose that $g_{1}^{-1}g_2 \in H$. We show both subset inclusions.

$g_1 H \subseteq g_2 H$ : Let $x \in g_1 H$. Then $x = g_1 h$ for some $h\in H$. Then $$g_{2}^{-1} = g_{2}^{-1}g_1 h\in H$$
Multiplying on the left by $g_2$: $g_2 g_2^{-1} x = x \in g_2 H$. The inclusion $g_2 H \subseteq g_1 H$ follows similarily.

## Theorem 
Let $H\leq G$. Then the left (right) cosets partition $G$.

## Definition 
Let $H\leq G$. The index of $H$ in $G$, dentoed by $[G:H]$, is the number of cosets of $H$ in $G$.


## Lemma & HW Problem
$g_1 H = g_2 H$ iff $Hg_{1}^{-1} = Hg_{2}^{-1}$

## Theorem
Let $H\leq G$. The number of left (and right) cosets

Define $\phi: \mathbb{L}\rightarrow\mathbb{R}$ where $\mathbb{L}$ and $\mathbb{R}$ deonte the left and right cosets respectively. *finish proof on page 75*

* Let $H\leq G$, then $|H| = |gH|$ (preliminary for [[lagrange's theorem]])