---
title: "Exercise 2A Problem 10"
date: 2022-06-25T22:17:50+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 10 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_m$ is linearly independent in $V$ and $w \in V$. Prove that if $v_1 + w, \dots, v_m + w$ is linearly dependent, then $w \in \textrm{span}(v_1, \dots, v_m)$

## Solution
We prove the contrapositive - let $w$ $\cancel{\in}$ $\textrm{span}(v_1, \dots, v_m)$, then for $a_1,\dots,a_m \in \mathbb{F}$ we have:
$$0 = a_1(v_1 + w) + a_2(v_2 + w) + \dots + a_m(v_m + w)$$
From which it follows that $-w\sum_{i=1}^{m}a_i = a_1v_1 + \dots + a_mv_m$ implying that $\sum_{i=1}^{m}a_i = 0$ for otherwise $w$ would be in the span of $v_1, \dots, v_m$:
$$w = -\frac{a_1}{\sum_{i=1}^{m}a_i}v_1 - \dots - \frac{a_m}{\sum_{i=1}^{m}a_i}v_m$$
But $\sum_{i=1}^{m}a_i = 0$ implies that the left hand side in $-w\sum_{i=1}^{m}a_i = a_1v_1 + \dots + a_mv_m$ equals $0$, therefore by the linear independence of $v_1, \dots, v_m$ we must have $a_1 = a_2 = \dots = a_m = 0$. Thus if $w$ $\cancel{\in}$ $\textrm{span}(v_1, \dots, v_m)$, then $v_1 + w, v_2 + w, \dots, v_m + w$ is linearly independent.



