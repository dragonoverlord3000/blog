---
title: "Exercise 2A Problem 7"
date: 2022-06-25T19:11:24+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove or give counterexample: If $v_1, v_2, \dots, v_m$ is a linearly independent list of vectors in $V$, then 
$$5v_1 - 4v_2, v_2, v_3, \dots, v_m$$
is linearly independent.

## Solution
By the linear independence of $v_1, v_2, \dots, v_m$, we must have that
$$0 = a_1v_1 + a_2v_2 + \dots + a_mv_m$$
$$=\frac{a_1}{5}\left(5v_1 - 4v_2\right) + \left(a_1\frac{9}{4} + a_2\right)v_2 + a_3 v_3 + \dots + a_m v_m$$
implies $a_1 = a_2 = \dots = a_m = 0$ which in turn implies $\frac{a_1}{5} = a_1\frac{9}{4} + a_2 = a_3 = \dots = a_m = 0$, thus the list $5v_1 - 4v_2, v_2, v_3, \dots, v_m$ is linearly independent if the list $v_1, v_2, v_3, \dots, v_m$ is.












