---
title: "Exercise 2B Problem 3"
date: 2022-06-26T13:51:41+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U$ be the subspace of $\mathbb{R}^5$ defined by
$$U = \lbrace (x_1,x_2,x_3,x_4,x_5) \in \mathbb{R}^5 | x_1 = 3x_2 \thinspace \textrm{and} \thinspace x_3 = 7x_4 \rbrace$$
Find a basis for $U$

(b) Extend the basis in part (a) to a basis of $\mathbb{R}^5$

(c) Find a subspace $W$ of $\mathbb{R}^5$ such that $\mathbb{R}^5 = U \oplus W$


## Solution
> (a) Any vector in $U$ can be written as $(x,x,y,y,z)$, therefore by theorem 2.29 the list $(1,1,0,0,0),(0,0,1,1,0),(0,0,0,0,1)$ is a basis for $U$

> (b) Extend the basis for $U$ above by appending $(1,0,0,0,0),(0,0,1,0,0)$ to the list by the linear dependence lemma - T2.21.

> (c) $W = \lbrace (x,0,y,0,0) | x,y \in \mathbb{R} \rbrace$ is spanned by $(1,0,0,0,0),(0,0,1,0,0)$ and therefore by *(b)* $U + W = \mathbb{R}^5$. Moreover if $u \in U$ and $w \in W$ and $(x,x,y,y,z) = u = w = (0,x^\prime,0,y^\prime,0)$, then by the first and second coordinate we have that $x^\prime = x = 0$ and $y^\prime = y = 0$ by the third and fourth coordinate and by the fifth coordinate $z = 0$, therefore $U \cap W = \lbrace 0 \rbrace$.











