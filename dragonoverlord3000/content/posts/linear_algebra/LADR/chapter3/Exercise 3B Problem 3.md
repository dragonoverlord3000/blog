---
title: "Exercise 3B Problem 3"
date: 2022-06-30T20:21:43+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_m$ is a list of vectors in $V$. Define $T \in \mathcal{L}(\mathbb{F}^m, V)$ by
$$T(z_1, \dots, z_m) = z_1v_1 + \dots + z_mv_m$$

> (a) What property of $T$ corresponds to $v_1, \dots, v_m$ spanning $V$?

> (b) What property of $T$ corresponds to $v_1, \dots, v_m$ being linearly independent?


## Solution
> (a) If $v_1, \dots, v_m$ spans $V$, then we can choose $z_1, \dots, z_m \in \mathbb{F}$ such that $(z_1, \dots, z_m) \in \mathbb{F}^m$ is mapped to any $v$ we want by the definition of span. This corresponds to surjectivity for $T$.

> (b) By theorem 2.29 we have that every $(z_1, \dots, z_m) \in \mathbb{F}^m$ is mapped to a unique vector in $V$ if $v_1, \dots, v_m$ is a linearly independent list. This is exactly injectivity by definition 3.15.



