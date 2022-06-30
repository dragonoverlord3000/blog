---
title: "Exercise 3A Problem 11"
date: 2022-06-29T10:06:47+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $V$ is finite-dimensional. Prove that every linear map on a subspace of $V$ can be extended to a linear map on $V$. In other words, show that if $U$ is a subspace of $V$ and $S \in \mathcal{L}(U,W)$, then there exists $T \in \mathcal{L}(V,W)$ such that $Tu = Su$ for all $u \in U$

## Solution
Let $u_1, \dots, u_m$ be a basis for $U$ and extend it to the basis $u_1, \dots, u_m, w_1, \dots, w_n$ of $V$, then by theorem 3.5 we can uniquely define the linear map $T \in \mathcal{L}(V,W)$ as follows: 

$$Tu_i = Su_i$$
$$Tw_i = 0$$

Then if $v \in U = \textrm{span}(u_1, \dots, u_m)$ by the fact that $u_1, \dots, u_m$ is a basis and therefore a spanning list. But this implies that there exist $a_1, \dots, a_m \in \mathbb{F}$ implying:
$$Tv = T(a_1u_1 + \dots + a_mu_m) \stackrel{D3.2}{=} a_1 T u_1 + \dots + a_m T u_m$$
$$= a_1 Su_1 + \dots + a_m Su_m \stackrel{D3.2}{=} S(a_1u_1 + \dots + a_mu_m) = Sv$$
Therefore $T$ is a linear map with the desired property that $Tu = Su$ for all $u \in U$.

