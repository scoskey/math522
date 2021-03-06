---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 522 homework

[Submit with gradescope](https://www.gradescope.com/courses/170391)

## Weeks 13-14 (Due Thursday, December 10)

1. (Kunen IV.7.10, part 1) Let $\aleph\_0\leq\kappa\lt\lambda$ and let $\mathbb P=Fn(\kappa,\lambda)$. Show that $\lambda$ is countable in $V[G]$, and all cardinals of $V$ above $\lambda$ remain cardinals in $V[G]$.
2. (Kunen IV.7.10, part 2) With $\mathbb P$ as above, show that if $V$ satisfies the GCH then $V[G]$ satisfies the GCH.
3. (21.1) Show that if $\mathbb P=Fn(\omega,\omega)$ and $G$ is $V$-generic, then $g=\bigcup G$ is not dominated by any element of the Baire space of $V$.
4. (23.1) Show that random forcing, together with $[\emptyset]$, forms a complete Boolean algebra. (A Boolean algebra $B$ is complete if every subset $X\subset B$ has a least upper bound.)

## Week 12 (Due Thursday, November 19)

1. (19.1) Let $\mathcal G\subset Fn(\kappa,\omega)$ be uncountable. Show that $\mathcal F=\set{dom(f)\mid f\in\mathcal G}$ is uncountable.
2. (Kunen III.2.7) If $\kappa$ is a singular cardinal, show that there is a family $\mathcal F$ of $2$-element subsets of $\kappa$ with no subfamily of size $\kappa$ that forms a Delta system. Hint: Let $\theta$ be the cofinality of $\kappa$. Elements of $\mathcal F$ will contain one element below $\theta$ and one element above $\theta$.
3. (Kunen IV.3.18) Let $\mathbb P$ be a countable partial order and let $J$ be a set of size $\aleph\_1$ in $V$. Let $G$ be generic, and let $E$ be an uncountable subset of $J$ in $V[G]$. Prove that there is an uncountable subset $E'\subset E$ in $V$. Hint: $E'=\set{j\in J\mid p\Vdash \check j\in\dot E}$.

## Week 10 (Due Thursday, November 5)

1. (16.1) In many cases it is more convenient to use $g=\bigcup G$ instead of $G$ itself. Write down a name $\gamma$ such that $\gamma_G=g$ whenever $G$ is a filter and $g=\bigcup G$.
2. (Kunen IV.2.8) Let $\tau=\set{(\emptyset,p),(\set{(\emptyset,q)},r)}$. There are eight possibilities for whether $p,q,r$ are $\in G$ or $\notin G$. Compute $\tau\_G$ in all eight cases.
3. (Kunen IV.2.16) Given $a\in V[G]$ we showed how to produce a name for $b\in V[G]$ such that $\bigcup a\subset b$. Show how to produce a name for $b\in V[G]$ such that $\bigcup a=b$. Hint: Let $\tau$ be a name for $a$ and define the name $\pi=\set{(\theta,p):(\exists(\sigma,q)\in\tau)(\exists r)\;(\theta,r)\in\sigma\wedge p\leq r\wedge p\leq q}$.
4. (Kunen IV.2.28) Give an example of $\mathbb P$, a sentence $\psi$ of the forcing language, and distinct generic filters $G,H$ such that $V[G]=V[H]$ and $V[G]\models\psi$ and $V[H]\models\neg\psi$. Hint: Use a finite $\mathbb P$ so that $V[G]=V[H]=V$, and write a sentence about the canonical name $\Gamma$ for the generic filter.

## Week 9 (Due Tuesday, October 27)

1. (Jech 14.5) Show that a filter $G\subset\mathbb P$ meets every dense set of $\mathbb P$ (in $V$) if and only if $G$ meets every maximal antichain of $\mathbb P$ (in $V$).
2. (15.1) Assume MA. Let $\mathcal F$ be an \emph{almost disjoint} family of infinite subsets of $\omega$: for all $A,A'\in\mathcal F$ we have that $A\cap A'$ is finite. Show that if $\abs{\mathcal F}<\mathfrak c$ then there exists a single infinite set $B$ such that $A\cap B$ is finite for all $A\in\mathcal F$. [Hint: consider the forcing $\mathbb P$ consisting of pairs $(s,F)$ where $s$ is a finite subset of $\omega$, $F$ is a finite subset of $\mathcal F$, and $(s',F')\leq(s,F)$ iff $s'\supset s$, $F'\supset F$, and whenever $A\in F$ we have $A\cap s'\subset s$.]

## Week 8 (Due Tuesday, October 20)

1. (Jech 14.1) Show that in the definition of generic filter, we can replace "for all $p,q\in G$ there exists $r\in G$ with $r\leq p,q$" with "for all $p,q\in G$ there exists $r$ with $r\leq p,q$". [Hint: show the set $\set{r\mid (r\leq p,q)\vee (r\text{ is incompatible with }p)\vee (r\text{ is incompatible with }q)}$ is dense.]
2. (Jech 14.3) Show that a filter $G\subset\mathbb P$ meets every dense set of $\mathbb P$ (in $V$) if and only if $G$ meets every dense open set of $\mathbb P$ (in $V$).
3. Suppose that $\mathbb P$ is not atomless. Show that there is a generic filter $G\subset\mathbb P$. (Recall $\mathbb P$ is atomless if for every $p\in\mathbb P$ there exist $q,r\leq p$ such that $q,r$ are incompatible.)
4. Suppose that $\mathbb P$ is atomless. Show that $\mathbb P$ has an infinite antichain.

## Week 7 (Due Tuesday, October 13)

1. (11.1) Let $P=(I\_n)$ and $Q=(J\_n)$ be interval partitions of $\omega$, and let $x,y\in2^\omega$. Prove that $\mathrm{Diff}(P,x)\subset \mathrm{Diff}(Q,y)$ if and only if for all but finitely many $m$ there exists $n$ such that $I\_n\subset J\_m$ and $x\restriction I\_n=y\restriction I\_n$.
2. (12.1) If $A\subset 2^\omega$ is null, then there exists a closed set $K\subset 2^\omega\setminus A$ with the property that whenever $V\_s\cap K\neq\emptyset$ we have $V\_s\cap K$ is nonnull.  
   Hint: First show that there exists a closed set $C\subset 2^\omega\setminus A$ which is non-null. Let $D$ be the union of all basic open sets $V\_s$ such that $m(V\_s\cap C)=0$, and show that $m(D)=0$. Finally let $K=C\setminus D$ and show that $K$ has the desired properties.]

## Week 6 (Due Tuesday, October 6)

1. (9.1) Show that there is a homeomorphism between co-countable subsets of $\mathbb R$ and $2^\omega$.
2. (9.2) For $V\_s$ a basic open set of $2^\omega$, let $m(V\_s)=2^{-\abs{s}}$. Then $m$ extends to a measure on the Borel sets of $2^\omega$ (take this for granted). Show that there is a measure-preserving bijection between $[0,1]$ and $2^\omega$, after possibly throwing away countable subsets of each.
3. (10.1) Find a morphism behind the proof of the inequality $non(\mathcal I)\leq cof(\mathcal I)$ (Lemma 8.5). Check that it is dual to a morphism behind the inequality $add(\mathcal I)\leq cov(\mathcal I)$.
4. (10.2) Find a morphism behind the proof of the inequality $\mathfrak b\leq non(\mathcal M)$ (Theorem 9.4). Check that it is dual to a morphism behind the inequality $cov(\mathcal M)\leq\mathfrak d$.

## Week 5 (Due Tuesday, September 29)

1. (7.2) Find an example of a meager subset of $\omega^\omega$ which is not in $\mathcal K\_\sigma$.
2. (7.3) Let $X$ be the space $\mathbb R^\omega$ with the product topology. Decide whether $X$ is $\sigma$-compact.
3. (8.1) Show that $\mathrm{cof}(\mathcal K\_\sigma)=\mathfrak d$.
4. (8.2) Let $\mathcal I$ be the ideal of countable subsets of $\mathbb R$. Find the values of the four cardinal characteristics of $\mathcal I$.

## Weeks 3-4 (Due Tuesday, September 22)

1. (5.2) Prove the well-ordering principle: If $A$ is any set, then there exists a binary relation $\leq$ which is a well-order of $A$. [Use Zorn's Lemma!]
2. (5.3) If $A$ is an infinite set, show that $\abs{A}$ is equal to $\aleph\_\alpha$ for some ordinal $\alpha$.
3. (6.2) Give an example of an open subset of $\omega^\omega$ which is not closed.
4. (6.3) Show that $\omega^\omega$ is homeomorphic to its product with itself $\omega^\omega\times\omega^\omega$.

## Week 2 (Due Thursday, September 10)

1. (3.2) Prove that the properties (a)--(c) of a measure imply *continuity from below*: if $A\_n$ is an increasing sequence of sets and $A=\bigcup A\_n$, then $m(A)=\sup m(A\_n)$. Then prove *continuity from above*: if $A\_n$ is a decreasing sequence of sets, $m(A\_n)$ is finite, and $A=\bigcap A\_n$, then $m(A)=\inf m(A\_n)$.
2. (3.4) Prove directly from the definition of null set that the null sets are closed under countable unions. (The definition of $A$ is null: for all $\epsilon>0$ there exist intervals $I\_n$ such that $A\subset\bigcup I\_n$ and $\sum l(I\_n)\lt\epsilon$.)
3. (4.1) Show that the following sets are all in bijection with one another: $\mathbb R$, $(0,1)$, $(0,\infty)$, $\mathcal P(\mathbb N)$, and $\set{A\in P(\mathbb N)\mid A\text{ is infinite}\}$.
4. (4.2) Which of the following categories satisfy the analog of the Cantor--Schroder--Bernstein theorem? (That is, monomorphisms $A\to B\to A$ implies isomorphism $A\cong B$.) linear orders with order-preserving maps; groups with group homomorphisms; topological spaces with continuous maps; topological spaces with piecewise continuous maps.

## Week 1 (Due Tuesday, September 1)

1. (1.1) With the definition of $C+C'$ for Dedekind cuts, show that addition is commutative and associative.
2. (1.4) Show that any two complete ordered fields are isomorphic as ordered fields. [Hint: observe that both must contain a copy of $\mathbb Q$ which is dense.]
3. (2.1) Compute the sum of the lengths of all of the intervals removed from $[0,1]$ in the construction of the Cantor set. What if some fraction other than $1/3$ is removed at each stage?
4. (2.2) Prove proposition 2.4 in the notes: $A$ is nowhere dense iff $\bar A$ contains no intervals of positive-length iff $A$ is non-dense in every open set.

<script type='text/x-mathjax-config'>
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true
    },
    TeX: {
      Macros: {
        set: ["{\\left\\{ #1 \\right\\}}", 1],
        abs: ["{\\left| #1 \\right|}", 1],
        lt: ["<"]
      }
    }
  });
</script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML'></script>