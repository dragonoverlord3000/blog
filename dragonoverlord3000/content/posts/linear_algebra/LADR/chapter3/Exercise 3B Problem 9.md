---
title: "Exercise 3B Problem 9"
date: 2022-07-01T18:43:47+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 9 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $T \in \mathcal{L}(V,W)$ is injective and $v_1, \dots, v_n$ is linearly independent in $V$. Prove that $Tv_1, \dots, Tv_n$ is linearly independent in $W$

## Solution
Let $a_1, \dots, a_n \in \mathbb{F}$ such that
$$0 = a_1Tv_1 + \dots + a_nTv_n \stackrel{D3.2}{=} T(a_1v_1 + \dots + a_nv_n)$$
Then injectivity implies $a_1v_1 + \dots + a_nv_n = 0$ and linear independence of $v_1, \dots, v_n$ then implies $a_1 = \dots = a_n = 0$ which in turn implies that $Tv_1, \dots, Tv_n$ is a linearly independent list in $W$.





