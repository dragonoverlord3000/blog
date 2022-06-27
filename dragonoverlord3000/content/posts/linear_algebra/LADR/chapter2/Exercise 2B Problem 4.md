---
title: "Exercise 2B Problem 4"
date: 2022-06-26T14:47:45+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U$ be the subspace of $\mathbb{C}^5$ defined by
$$U = \lbrace (z_1,z_2,z_3,z_4,z_5) \in \mathbb{C}^5 | 6z_1 = z_2 \thinspace \textrm{span} \thinspace z_3 + 2z_4 + 3z_5 = 0 \rbrace$$
Find a basis of $U$.

(b) Extend the basis in part (a) to a basis of $\mathbb{C}^5$

(c) Find a subspace $W$ of $\mathbb{C}^5$ such that $\mathbb{C}^5 = U \oplus W$

## Solution
> (a) Any vector in $U$ can be written as $(x,6x,-2y - 3z,y,z)$, therefore a basis for $U$ is the list $(1,6,0,0,0), (0,0,-2,1,0), (0,0,-3,0,1)$ as any vector $u = (x,6x,-2y - 3z,y,z) \in U$ can be written uniquely as the linear combination $(x,6x,-2y - 3z,y,z) = x(1,6,0,0,0) + y(0,0,-2,1,0) + z(0,0,-3,0,1)$, therefore by theorem 2.29 it's a basis for $U$.

> (b) As $(1,0,0,0,0),(0,0,1,0,0) \in \mathbb{C}^5$ and are linearly independent with the list $(1,6,0,0,0), (0,0,-2,1,0), (0,0,-3,0,1)$, therefore the basis for $U$ can be extended to a basis (see theorem 2.23) for $\mathbb{C}^5$ as such: $(1,6,0,0,0), (0,0,-2,1,0), (0,0,-3,0,1), (1,0,0,0,0), (0,0,1,0,0)$.

> (c) By (b) we have $\textrm{span}((1,0,0,0,0),(0,0,1,0,0)) \cap U = 0$ and $\textrm{span}((1,0,0,0,0),(0,0,1,0,0)) + U = \mathbb{C}^5$. Therefore $W = \textrm{span}((1,0,0,0,0),(0,0,1,0,0))$ has the property $W \oplus U = \mathbb{C}^5$.
























