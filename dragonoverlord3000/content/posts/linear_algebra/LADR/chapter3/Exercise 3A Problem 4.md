---
title: "Exercise 3A Problem 4"
date: 2022-06-28T14:30:37+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $T \in \mathcal{L}(V,W)$ and $v_1, \dots, v_m$ is a list of vectors in $V$ such that $Tv_1, \dots, Tv_m$ is a linearly independent list in $W$. Prove that $v_1, \dots, v_m$ is linearly independent.

## Solution
Let $a_1, \dots, a_m \in \mathbb{F}$ such that $0 = a_1v_1 + \dots + a_mv_m$, then:
$$0 \stackrel{T3.11}{=} T(0) = T(a_1v_1 + \dots + a_mv_m) \stackrel{D3.2}{=} a_1 Tv_1 + \dots + a_m Tv_m$$
Then the linear independence of $Tv_1, \dots, Tv_m$ implies $a_1 = \dots = a_m = 0$ and this in turn implies the linear independence of $v_1, \dots, v_m$ by theorem 2.17.






