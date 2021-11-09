#chapter3
##### Definition of Group
A group $(G, \circ )$ is a set $G$ together with a law of composition $(a,b)\rightarrow a\circ b$ that satisfies the following axioms
* The law of composition is associative $$(a\circ b)\circ c = a \circ (b\circ c)$$ for $a,b,c\in G$
* There exists an element $e\in G$ called the indentity element such that for any element $a\in G$ $$e\circ a = a\circ e  = a$$
* For each element $a\in G$, there exists an inverse element in $G$, denoted by $a^{-1}$, such that $$a\circ a^{-1} = a^{-1}\circ a = e$$

A group $G$ with the property that $a\circ b = b\circ a$ for all $a,b \in G$ is called [[abelian]] or commutative.


##### Properties of Groups

Proposition
The identity element in a group $G$ is unique; that is, there exists only one element $e\in G$ such that $eg = ge = g$ for all $g\in G$

Proposition
If $g$ is any element in a group $G$, then the inverse of $g$, denoted by $g^{-1}$is unique.

Proposition
Let $G$ be a group. If $a,b\in G$ then $(ab)^{-1} = b^{-1}a^{-1}$

Proposition
Let G be a group. For any $a\in G$, $(a^{-1})^{-1} = ae = a$

Proposition
Let $G$ be a group and $a$ and $b$ be any two elements in $G$. Then the equations $ax = b$ and $xa = b$ have unique solutions in $G$.

Proposition
If $G$ is a group and $a,b,c\in G$ then $ba = ca$ implies $b = c$and $ab = ac$ implies $b = c$

##### Theorem
In a group, the usual laws of exponents hold; that is, for all $g, h\in G$
* $g^m g^n = g^{m+n}$ for all $m,n\in \mathbb{Z}$
* $(g^m )^n = g^{mn}$ for all $m,n\in \mathbb{Z}$
* $(gh)^n = (h^{-1}g^{-1})^{-n}$ for all $n\in\mathbb{Z}$. Furthermore, if $G$ is [[abelian]], then $(gh)^n = g^n h^n$