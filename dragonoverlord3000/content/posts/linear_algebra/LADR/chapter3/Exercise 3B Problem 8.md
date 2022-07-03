---
title: "Exercise 3B Problem 8"
date: 2022-07-01T18:13:20+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $V$ and $W$ are finite-dimensional with $\dim V \geq \dim W \geq 2$. Show that $\lbrace T \in \mathcal{L}(V,W) | T$ is not surjective $ \rbrace$ is not a subspace of $\mathcal{L}(V,W)$

## Solution
We can copy the setup in the solution to [P3B7](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter3/exercise-3b-problem-7/):

Let $v_1, v_2, \dots, v_n$ be a basis for $V$ and let $w_1, w_2, \dots, w_m$ be a basis for $W$, then define $T_1, T_2 \in \mathcal{L}(V,W)$ by $T_1v_{i} = 0$, $T_1v_{j} = w_{\textrm{min}(j,m)}$  and $T_2v_{i} = w_{i}$, $T_2v_{j} = 0$ and $T_2v_{i} = w_{\textrm{min}(i,m)}$. Where $i = 1,3,5,\dots$ and $j = 2,4,6,\dots$

Then $\textrm{range} \thinspace T_1 = \textrm{span}(v_2,v_4,\dots,v_{2k})$ and $\textrm{range} \thinspace T_2 = \textrm{span}(v_1,v_3,\dots,v_{2k \pm 1})$, but the sum of $T_1$ and $T_2$ is:
$$(T_1 + T_2)(v) = T_1v + T_2v = w_{even} + w_{odd} = w$$
I.e. $T_1 + T_2$ maps to $\textrm{span}(w_1, \dots, w_m) = W$ and since we can find a list of vectors $u_1, \dots, u_m \in V$ such that $T_1 + T_2$ maps these to any $w \in W$ of our choosing, by construction, it is surjective. Implying that $\lbrace T \in \mathcal{L}(V,W) | T$ is not surjective $ \rbrace$ is not closed under addition.








