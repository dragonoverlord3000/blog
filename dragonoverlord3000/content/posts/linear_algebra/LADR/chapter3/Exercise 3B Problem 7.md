---
title: "Exercise 3B Problem 7"
date: 2022-07-01T09:13:02+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Suppose $V$ and $W$ are finite-dimensional with $\dim V \geq \dim W \geq 2$. Show that $\lbrace T \in \mathcal{L}(V,W) | T $ is not injective $\rbrace$ is not a subspace of $\mathcal{L}(V,W)$

## Solution
Let $v_1, v_2, \dots, v_n$ be a basis for $V$ and let $w_1, w_2, \dots, w_m$ be a basis for $W$, then define $T_1, T_2 \in \mathcal{L}(V,W)$ by $T_1v_{i} = 0$, $T_1v_{j} = w_{j}$  and $T_2v_{i} = w_{i}$, $T_2v_{j} = 0$ and $T_2v_{i} = w_{i}$. Where $i = 1,3,5,\dots$ and $j = 2,4,6,\dots$

Then $\textrm{null} \thinspace T_1 = \textrm{span}(v_1,v_3,\dots,v_{2k \pm 1})$ and $\textrm{null} \thinspace T_2 = \textrm{span}(v_2,v_4,\dots,v_{2k})$, but the sum of $T_1$ and $T_2$ is:
$$(T_1 + T_2)(v) = T_1v + T_2v = v_{even} + v_{odd} = v$$
I.e. $T_1 + T_2$ is the identity map and therefore has $\textrm{null} \thinspace (T_1 + T_2) = \lbrace 0 \rbrace$ which implies injectivity by theorem 3.16. Therefore $\dim V \geq \dim W \geq 2$. Show that $\lbrace T \in \mathcal{L}(V,W) | T $ is not injective $\rbrace$ is not closed under addition.




