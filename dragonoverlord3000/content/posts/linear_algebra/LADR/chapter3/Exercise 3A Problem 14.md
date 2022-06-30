---
title: "Exercise 3A Problem 14"
date: 2022-06-29T19:44:19+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 14 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $V$ is finite-dimensional with $\dim V \geq 2$. Prove that there exist $S,T \in \mathcal{L}(V,V)$ such that $ST \neq TS$

## Solution
Let $v_1, v_2$ be a linearly independent list of $V$ which exist as per the restriction $\dim V \geq 2$ and definition 2.36. Now we can uniquely the linear maps $S$ and $T$ as the extension described in [P3A10](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter3/exercise-3a-problem-10/) to the subspace $U = \textrm{span}(v_1, v_2)$ and where $T,S$ is defined uniquely on $U$ by theorem 3.5 and the following:
$$Sv_1 = v_2 \thinspace\thinspace\thinspace\thinspace\thinspace\thinspace Sv_2 = v_1$$
$$Tv_1 = v_1 \thinspace\thinspace\thinspace\thinspace\thinspace\thinspace Tv_2 = -v_2$$
Then it follows that:
$$STv_2 = S(-v_2) \stackrel{D3.2}{=} -Sv_2 = -v_1$$
$$TSv_2 = Tv_1 = v_1$$
But as $v_1 \neq 0$ by the fact that $v_1$ is a part of a linearly independent list implying $ST \neq TS$.









