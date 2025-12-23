---
layout: single
title: "Circulant Weighing Matrices"
mathjax: true
permalink: /circulant-weighing-matrices/
---


A *weighing matrix* $W = W(n,k)$ with weight $k$ is a square
matrix of order $n$ and entries $w_{i,j}$ in {$-1,0, +1$} such that
$WW^T=kI_n$. For
example, when $k=n$ this is a Hadamard matrix.

A circulant weighing matrix $CW(n,k)$ is a special type of
weighing matrix in which every row except for the first is a right
cyclic shift of the previous row.  Equivalently, the first row viewed
as a sequence has constant autocorrelation $0$.

Let $P$ be the set of locations with a $+1$ in the first
row, and $N$ be the locations with a $-1$.  Then
$|P|+|N|=k$.  It is known that

- $k = s^2$ for some integer $s$,
- $ \|P\| = (s^2+s)/2$,
- $\|N\| = (s^2-s)/2$.

A circulant weighing matrix $W$ is *proper* if the nonzeros in $P$ and $N$
are not all in a coset of a proper subgroup of ${\mathbb
Z}/n{\mathbb Z}$.  The existence of proper matrices is the 
focus of this database.  See
[my paper with Arasu and Zhang](https://link.springer.com/article/10.1007/s12095-021-00492-0)
for some of the methods used to determine existence of these matrices.


As with difference sets, there are numerous results about the
existence of circulant weighing matrices.  Strassler in 1997 gave a
table of results for $n&le;200$ and $s&le; 10$.  This
database attempts to bring together all known results about cases in
Strassler's table, and extend the table further.



<a href="https://doi.org/10.5281/zenodo.10775927"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.15442180.svg" alt="DOI"></a>

