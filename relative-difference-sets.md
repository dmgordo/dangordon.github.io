---
layout: single
title: "Relative Difference Sets"
mathjax: true
permalink: /relative-difference-sets/
---


A *relative* $(m,n,k,\lambda)$-*difference set* in a group $G$ of
order $mn$ relative to a normal subgroup $N$ of order $n$
is a subset
{$ r_1, r_2, ..., r_k $} of $G$ 
such that the element $R = \Sigma r_i$ in the group ring
$Z[G]$ satifies the difference set equation:

$R R^{-1} = n + \lambda (G-N)$,

where $n = k-\lambda$.  In other words, the differences of elements in
$R$ hit all elements of $G$ exactly $\lambda$ times, except for the
"forbidden subgroup" $N$.

It is known that an $(m,n,k,\lambda)$-relative difference set is a
lifting of a $(m,k,\lambda n)$-difference set,
and a longstanding open problem is: what difference sets lift to
relative difference sets?  It is conjectured that the only nontrivial
cyclic difference sets that lift to relative difference sets have parameters:

$$
\left( \frac{q^d-1}{q-1},q^{d-1},q^{d-2}(q-1) \right),
$$

those of the complements of Singer difference sets.

[My forthcoming paper](https://arxiv.org/abs/2501.14924) in *Journal of Algebraic Combinatorics* 
gives results on a search for lifts of difference sets, showing that
up to $k=256$ these are the only known cyclic difference sets with
lifts, with four possible exceptions.

Information from this search is at:

<a href="https://doi.org/10.5281/zenodo.14735634"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.14735634.svg" alt="DOI"></a>

