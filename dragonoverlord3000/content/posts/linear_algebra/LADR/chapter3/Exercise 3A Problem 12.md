---
title: "Exercise 3A Problem 12"
date: 2022-06-29T13:03:01+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 12 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Suppose $V$ is finite-dimensional with $\dim V > 0$, and suppose $W$ is infinite-dimensional. Prove that $\mathcal{L}(V,W)$ is infinite-dimensional


## Solution
Let $w_1, w_2, \dots$ be an infinite sequence of linearly independent vectors in $W$ which exists as per [P2A14](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-14/). If we let $v_1, \dots, v_n$ be a basis of $V$, then by theorem 3.5 we can construct an infinite sequence of linear maps in $\mathcal{L}(V,W)$ by letting $T_i \in \mathcal{L}(V,W)$ be defined by $T_i v_j = w_{i+j-1}$. The sequence $T_1, T_2, \dots$ is linearly independent by the linear independence of $w_1, w_2, \dots$ - *Proof:*

If we let $a_1, \dots, a_m \in \mathbb{F}$ such that $a_1T_1 + \dots + a_mT_m = 0$, where the right hand side is the $0$ map on $V$. Then:
$$a_1w_1 + \dots + a_mw_m = a_1T_1v_1 + \dots + a_mT_mv_1$$ 
$$(a_1T_1 + \dots + a_mT_m)(v_1) = 0(v_1) = 0$$
Implying $a_1 = \dots = a_m = 0$ by the linear independence of $T_1, \dots, T_m$ for any $m \in \mathbb{N}$. [P2A14](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-14/) therefore implies that $\mathcal{L}(V,W)$ is infinite-dimensional.





