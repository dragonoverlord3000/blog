---
title: "Exercise 2A Problem 17"
date: 2022-06-26T10:37:44+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 17 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $p_0, p_1, \dots, p_m$ are polynomials in $\mathcal{P}_m(\mathbb{F})$ such that $p_j(2) = 0$ for each $j$. Prove that $p_0, p_1, \dots, p_m$ is not linearly independent in $\mathcal{P}_m(\mathbb{F})$

## Solution
We know that $z-2 | p_i$ for all $i$, therefore we now denote $q_i$ as the polynomial $p_i/(z-2)$. Therefore:
$$0 = a_0p_0 + a_1p_1 + \dots + a_mp_m$$
Is only true *in general* if and only if:
$$0 = a_0q_0 + a_1q_1 + \dots + a_mq_m$$
But $q_i$ has degree at most $m-1$ and the linearly independent list $1,z,\dots,z^{m-1}$ spans $\mathcal{P}_{m-1}(\mathbb{F})$, therefore by theorem 2.23 $q_0, q_1, \dots, q_m$ is linearly dependent implying that there exist $a_0, a_1, \dots, a_m$, not all zero, such that $0 = a_0q_0 + a_1q_1 + \dots + a_mq_m$ and by extension $0 = a_0p_0 + a_1p_1 + \dots + a_mp_m$.





