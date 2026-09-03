---
permalink: /ljcr/
title: "The La Jolla Combinatorics Repository"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

In 1996 I started an online database of coverings designs.
Over the years it grew and changed, from static HTML pages for each
covering, to a MySQL database using PHP, and then
AWS EC2 and RDS instances.  Hundreds of researchers
have contributed tens of thousands of improved coverings over the
years, and I've added databases for circulant weighing matrices and
several types of difference sets, 

After thirty years my databases are being retired.  The covering
designs database was frozen after March 1, 2026, and in August the AWS
servers were shut down.  The data will remain available; each database
is stored on
[github](https://github.com/dmgordo?tab=repositories), with a mirror
at
[zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Gordon%2C%20Daniel%20M.%22&l=list&p=1&s=10&sort=bestmatch), as a `json`
file.  Python code and a jupyter notebook are provided to facilitate reading and
processing the data.


The navigation bar at the top of this page leads to descriptions of
each of the combinatorial objects and their databases, but if you just
want to go to one, the links are:

- ![](https://zenodo.org/badge/DOI/10.5281/zenodo.10779737.svg) [Covering designs](https://zenodo.org/doi/10.5281/zenodo.10779736)
- ![](https://zenodo.org/badge/DOI/10.5281/zenodo.15442142.svg) [Difference sets](https://zenodo.org/doi/10.5281/zenodo.10775931)
- ![](https://zenodo.org/badge/DOI/10.5281/zenodo.7713113.svg) [Signed difference sets](https://zenodo.org/doi/10.5281/zenodo.7473882)
- ![](https://zenodo.org/badge/DOI/10.5281/zenodo.14735633.svg) [Cyclic relative difference sets](https://zenodo.org/doi/10.5281/zenodo.14735633)
- ![](https://zenodo.org/badge/DOI/10.5281/zenodo.15442180.svg) [Circulant weighing matrices](https://zenodo.org/doi/10.5281/zenodo.10775927)

Each of these databases is being made available under a
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. You
are free to share and adapt the data any way you like, as long as you
give attribution and indicate what changes have been made.


If you have any issues using one of the databases, or notice any
errors or omissions, please contact me at dmgordo *at* gmail *dot* com.


## Why these combinatorial objects?

The collection of databases may seem random, but aside from covering
designs, they are related.  All of these objects are equivalent to elements of a group ring satisfying the equation:

$A A^{-1} = k + \lambda (G-N)$,

where:
- The coefficients of $A$ are in $\lbrace 0,1 \rbrace$ for difference sets and relative difference sets, and $\lbrace 0,\pm 1 \rbrace$ for signed difference sets and circulant weighing matrices,
- The normal subgroup $N$ of $G$ is just the identity for everything except relative difference sets,
- $G$ is cyclic and $\lambda =0$ for circulant weighing matrices.

The diagram below illustrates their connections:
difference sets and circulant weighing matrices are both special cases of
signed difference sets.
Relative difference sets may be
constructed by lifting difference sets to a larger group, and
some circulant weighing matrices may be constructed from relative
difference sets.

```mermaid
---
config:
  theme: 'forest'
---
graph TB
    DS<-->RDS((RDS))
    RDS-->CWM
    subgraph SDS
    DS((DS))
    CWM((CWM))
    end
```

See the pages for each
object and the papers referenced there for more details.

