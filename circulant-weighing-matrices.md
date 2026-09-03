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

The following table from
[my recent paper](https://doi.org/10.1007/s10801-026-01515-w) 
summarizes our knowledge of 
proper $CW(n,k)$ with $n < 1000$ and $k \leq
19^2$. Most CW's come from smaller ones via a product construction.
Underlined numbers have CW's coming from a relative difference set,
numbers in **bold** come from other
constructions,
and  entries in boxes have sporadic $CW$s with constructions only
for those parameters (generally an older result or computer search).
Entries $cm$ are for all $m$ such that $cm \geq k$.
$CW(217,8^2)$ is the only entry with matrices from the Kronecker
construction and additional sporadic ones, and
$CW(511,16^2)$ is the only entry with matrices from both
the product and RDS constructions.

| $k$ | Known Proper $CW(n,k)$ |
|:---:|:------------------------|
| $2^2$ | $\boxed{2m}$, $\underline{7}$ |
| $3^2$ | $\underline{13}$, $\boxed{24}$, $\boxed{26}$ |
| $4^2$ | $14m$, $\underline{21}$, $\underline{31}$, $\boldsymbol{62}$, $\boxed{\underline{63}}$ |
| $5^2$ | $\underline{31}$, $\boxed{33}$, $\boxed{62}$, $\boxed{71}$, $\boxed{124}$, $\boxed{142}$ |
| $6^2$ | $26m$, $\boldsymbol{48m}$, $91$, $168$, $182$ |
| $7^2$ | $\underline{57}$, $\boxed{87}$, $\boxed{114}$, $\underline{171}$ |
| $8^2$ | $42m$, $62m$, $\underline{73}$, $\boxed{\underline{127}}$, $\boxed{217}$, $\boldsymbol{254}$, $434$, $\underline{511}$ |
| $9^2$ | $\underline{91}$, $\boxed{\underline{121}}$, $\boxed{182}$, $312$ |
| $10^2$ | $62m$, $66m$, $142m$, $217$, $231$, $434$, $497$, $868$, $994$ |
| $11^2$ | $\underline{133}$, $\underline{665}$ |
| $12^2$ | $182m$, $273$, $336m$, $403$, $546$, $744$, $806$, $819$ |
| $13^2$ | $\underline{183}$, $\underline{549}$ |
| $14^2$ | $114m$, $174m$, $342m$, $399$, $609$, $798$ |
| $15^2$ | $403$, $429$, $744$, $806$, $858$, $923$ |
| $16^2$ | $146m$, $254m$, $\underline{273}$, $\underline{341}$, $434m$, $\underline{511}$, $651$, $\boldsymbol{682}$, $\underline{819}$, $889$ |
| $17^2$ | $\underline{307}$ |
| $18^2$ | $182m$, $242m$, $624m$, $847$ |
| $19^2$ | $\underline{381}$ |

For larger $k$ almost all the entries come from the product or RDS constructions, so presumably many others remain to be found.

<a href="https://doi.org/10.5281/zenodo.10775927"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.15442180.svg" alt="DOI"></a>

