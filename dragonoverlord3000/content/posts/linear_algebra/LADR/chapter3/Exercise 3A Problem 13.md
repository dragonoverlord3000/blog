---
title: "Exercise 3A Problem 13"
date: 2022-06-29T13:34:10+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 13 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_m$ is a linearly independent list of vectors in $V$. Suppose also that $W \neq \lbrace 0 \rbrace$. Prove that there exist $w_1, \dots, w_m \in W$ such that no $T \in \mathcal{L}(V,W)$ satisfies $Tv_k = w_k$ for each $k = 1,\dots,m$

## Solution
As $w \neq \lbrace 0 \rbrace$, then there is a non-zero $w \in W$. If we now let $w = w_1 = \dots = w_m$, then because $v_1, \dots, v_m$ is linearly dependent, there exists $a_1, \dots, a_m \in \mathbb{F}$, not all zero, such that $0 = a_1v_1 + \dots + a_mv_m$. Applying $T$ on both sides, then imply:
$$0 \stackrel{T3.11}{=} T(0) = T(a_1v_1 + \dots + a_mv_m) \stackrel{D3.2}{=} w\sum_{i=1}^{m}a_{i} \thinspace\thinspace\thinspace\thinspace\thinspace\thinspace (\spadesuit)$$
If $\sum_{i=1}^{m}a_{i} = 0$, then we can change $T$ such that $Tv_j = 2w$ for some $j$ with $a_j \neq 0$, then:
$$0 \stackrel{T3.11}{=} T(0) = T(a_1v_1 + \dots + 2a_jv_j + \dots + a_mv_m)$$ 
$$= w\left(a_j + \sum_{i=1}^{m}a_{i}\right) \stackrel{D3.2}{=} a_jiw$$
And as $a_j \neq 0$ we must have $w = 0$ by [P1B2](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1b-problem-2/), this is a contradiction as we assumed $w \neq 0$. If $\sum_{i=1}^{m}a_{i} \neq 0$, then $(\spadesuit)$ implies $w = 0$ and we again have a contradiction.






