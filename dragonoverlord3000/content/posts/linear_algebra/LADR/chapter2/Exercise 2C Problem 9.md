---
title: "Exercise 2C Problem 9"
date: 2022-06-27T14:15:36+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 9 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_m$ is linearly independent in $V$ and $w \in V$. Prove that
$$\dim \textrm{span}(v_1 + w, \dots, v_m + w) \geq m - 1$$

## Solution
There are two cases, either $w \in \textrm{span}(v_1, \dots, v_m)$ or it is not. 

Given that $w$ $\cancel{\in}$ $\textrm{span}(v_1, \dots, v_m)$, then [P2A10](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-10/) implies $\dim \textrm{span}(v_1 + w, \dots, v_m + w) = m$ - this is the contrapositive of the problem statement in the exercise. 

Suppose on the other hand that $w \in \textrm{span}(v_1, \dots, v_m)$, then there are $b_1, \dots, b_m \in \mathbb{F}$ such that:
$$w = b_1v_1 + \dots + b_mv_m$$
Then if $a_1, \dots, a_m \in \mathbb{F}$ are such that:
$$0 \stackrel{\clubsuit}{=} a_1(v_1 + w) + a_2(v_2 + w) + \dots + a_m(v_m + w)$$
$$\stackrel{\spadesuit}{=} a_1v_1 + \dots + a_mv_m + w\sum_{i=1}^{m}a_i$$
$$= \left(a_1 + b_1\sum_{i=1}^{m}a_i\right)v_1 + \dots + \left(a_m + b_m\sum_{i=1}^{m}a_i\right)v_m$$
Which by the linear independence of $v_1, \dots, v_m$ implies that:
$$a_1 + b_1\sum_{i=1}^{m}a_i = \dots = a_m + b_m\sum_{i=1}^{m}a_i = 0$$
Adding all the left hand sides then imply:
$$\left(1 + \sum_{i=1}^{m}b_i\right)\left(\sum_{i=1}^{m}a_i\right) = 0$$
Then by the 'zero-rule' either $\sum_{i=1}^{m}a_i = 0$ in which case the linear independence of $v_1, \dots, v_m$ implies $a_1 = \dots = a_m = 0$ by $\spadesuit$, implying the linear independence of $v_1 + w, \dots, v_m + w$.

The other case is $\sum_{i=1}^{m} b_i = -1$, in this case we can let $a_i = b_i$ for all $i \in \lbrace 1, \dots, m \rbrace$, this would imply that there are scalars, not all zero, such that $\clubsuit$ holds i.e. we have linear dependence. By theorem 2.21 we can therefore remove $v_j + w$ if it has non-zero $a_j = b_j$ in $\clubsuit$ without decreasing the dimension of the list $v_1 + w, \dots v_m + w$. Then by repeating the steps above we arrive at:
$$\left(1 + \sum_{i=1 \land i \neq j}^{m}b_i\right)\left(\sum_{i=1 \land i \neq j}^{m}a_i\right) = 0$$
And since $b_j \neq 0$ and $\sum_{i=1}^{m}b_i = -1$ we must have $\sum_{i=1 \land i \neq j}^{m}b_i \neq -1$ implying that $\sum_{i=1 \land i \neq j}^{m}a_i = 0$ which by the same argument as above implies the linear independence of the list $v_1 + w, \dots, v_{j-1} + w, v_{j+1} + w, \dots, v_m + w$. Implying that $\dim \textrm{span}(v_1 + w, \dots, v_m + w) = m - 1$.

Therefore if $w = b_1v_1 + \dots + b_mv_m$ with $\sum_{i=1}^{m}b_i = -1$, then $\dim \textrm{span}(v_1 + w, \dots, v_m + w) = m - 1$ otherwise $\dim \textrm{span}(v_1 + w, \dots, v_m + w) = m$ $\square$. Thus $v_1 - w, \dots, v_m - w$.




