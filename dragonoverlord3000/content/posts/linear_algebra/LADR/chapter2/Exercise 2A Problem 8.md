---
title: "Exercise 2A Problem 8"
date: 2022-06-25T19:34:21+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove or give a counterexample: If $v_1, v_2, \dots, v_m$ is a linearly independent list of vectors in $V$ and $\lambda \in \mathbb{F}$ with $\lambda \neq 0$, then $\lambda v_1, \lambda v_2, \dots, \lambda v_m$ is linearly independent


## Solution
By the linear independence of $v_1, v_2, \dots, v_m$ we must have that
$$0 = a_1v_1 + a_2v_2 + \dots + a_mv_m = \frac{a_1}{\lambda}(\lambda v_1) + \frac{a_2}{\lambda}(\lambda v_2) + \dots + \frac{a_m}{\lambda}(\lambda v_m)$$
if and only if $a_1 = a_2 = \dots = a_m = 0$ by definition 2.17, but this is equivalent to $\frac{a_1}{\lambda} = \frac{a_2}{\lambda} = \dots = \frac{a_m}{\lambda} = 0$, thus the list $\lambda v_1, \lambda v_2, \dots, \lambda v_m$ is linearly independent.





