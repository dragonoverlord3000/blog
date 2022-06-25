---
title: "Exercise 2A Problem 6"
date: 2022-06-25T18:28:25+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, v_2, v_3, v_4$ is linearly independent in $V$. Prove that the list
$$v_1 - v_2, v_2 - v_3, v_3 - v_4, v_4$$
is also linearly independent.

## Solution
If $a_1, a_2, a_3, a_4 \in \mathbb{F}$, then 
$$0 = a_1(v_1 - v_2) + a_2(v_2 - v_3) + a_3(v_3 - v_4) + a_4v_4$$
$$a_1v_1 + (a_2 - a_1)v_2 + (a_3 - a_2)v_3 + (a_4 - a_3)v_4$$
Implies $a_1 = a_2 - a_1 = a_3 - a_2 = a_4 - a_3 = 0$ by the linear independence of $v_1, v_2, v_3, v_4$, but $a_1 = a_2 - a_1 = a_3 - a_2 = a_4 - a_3 = 0$ implies $a_1 = a_2 = a_3 = a_4 = 0$, thus the list $v_1 - v_2, v_2 - v_3, v_3 - v_4, v_4$ is linearly independent if the list $v_1, v_2, v_3, v_4$ is.




