---
title: "Exercise 2B Problem 6"
date: 2022-06-26T15:22:44+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, v_2, v_3, v_4$ is a basis of $V$. Prove that
$$v_1 + v_2, v_2 + v_3, v_3 + v_4, v_4$$
is also a basis of $V$.

## Solution
Let $a_1,a_2,a_3,a_4 \in \mathbb{F}$ with:
$$0 = a_1(v_1 + v_2) + a_2(v_2 + v_3) + a_3(v_3 + v_4) + a_4v_4$$
$$= a_1v_1 + (a_1 + a_2)v_2 + (a_2 + a_3)v_3 + (a_3 + a_4)v_4$$
Implying that $a_1 = a_1 + a_2 = a_2 + a_3 = a_3 + a_4 = 0$, by the linear independence of $v_1, v_2, v_3, v_4$, which in turn implies $a_1 = a_2 = a_3 = a_4 = 0$. thus 
$$v_1 + v_2, v_2 + v_3, v_3 + v_4, v_4$$
is a linear independent list of length 4, which by theorem 2.23 implies that it's also a spanning list and therefore a basis.






















