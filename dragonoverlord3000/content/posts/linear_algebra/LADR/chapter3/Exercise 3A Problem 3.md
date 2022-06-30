---
title: "Exercise 3A Problem 3"
date: 2022-06-28T13:47:26+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $T \in \mathcal{L}(\mathbb{F}^n, \mathbb{F}^m)$. Show that there exist scalars $A_{j,k} \in \mathbb{F}$ for $j = 1, \dots, m$ and $k = 1, \dots, n$ such that
$$T(x_1, \dots, x_n) = (A_{1,1} x_1 + \dots + A_{1,n}x_n, \dots, A_{m,1}x_1 + \dots + A_{m,n}x_n)$$
for every $(x_1, \dots, x_n) \in \mathbb{F}^{n}$

## Solution
Let $\mathbf{e}_{j}$ denote the vector in $\mathbb{F}^n$ with a $1$ at the $j$'th coordinate and $0$'s everywhere else. Then $\mathbf{e}_1, \dots, \mathbf{e}_n$ is the standard basis of  $\mathbb{F}^n$ as per Example 2.28.

Then for any $(x_1, \dots, x_n) \in \mathbb{F}^n$, the linearity of $T$ implies:
$$T(x_{1}, \dots, x_{n}) = T(x_{1}\mathbf{e}_{1} + \dots + x_{n}\mathbf{e}_{n}) = x_{1}T\mathbf{e}_{1} + \dots + x_{n}T\mathbf{e}_{n}$$
Now let $T\mathbf{e}_{j} = (A_{1,j}, \dots, A_{m,j})$ for all $j = 1,\dots,n$. This implies that:
$$T(x_{1}, \dots, x_{n}) = x_{1}T\mathbf{e}_{1} + \dots + x_{n}T\mathbf{e}_{n}$$ 
$$= x_{1}(A_{1,1}, \dots, A_{m,1}) + \dots + x_{n}(A_{1,n}, \dots, A_{m,n})$$
$$\stackrel{D1.12 \land D1.17}{=} (A_{1,1} x_1 + \dots + A_{1,n}x_n, \dots, A_{m,1}x_1 + \dots + A_{m,n}x_n)$$
And we're done (note the connection to matrix-vector multiplication).



