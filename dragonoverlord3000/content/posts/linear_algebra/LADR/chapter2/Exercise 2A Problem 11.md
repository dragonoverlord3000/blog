---
title: "Exercise 2A Problem 11"
date: 2022-06-25T22:36:59+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_m$ is linearly independent in $V$ and $w \in V$. Show that $v_1, \dots, v_m, w$ is linearly independent if and only if 
$$w \thinspace \cancel{\in} \thinspace \textrm{span}(v_1, \dots, v_m)$$

## Solution
Let $a_0, a_1, \dots, a_m \in \mathbb{F}$ such that:
$$0 = a_0w + a_1v_1 + a_2v_2 + \dots + a_mv_m$$
Then either $a_0 = 0$ which would imply $a_1 = a_2 = \dots = a_m = 0$ by the linear independence of $v_1, v_2, \dots, v_m$ or $a_0 \neq 0$ which would imply:
$$w = \frac{a_1}{a_0}v_1 + \dots + \frac{a_m}{v_m}$$
i.e. $w \in \textrm{span}(v_1, \dots, v_m)$. Implying that $a_0 = 0$ (and therefore linear independence of the list $v_1, \dots, v_m, w$) if and only if $w \thinspace \cancel{\in} \thinspace \textrm{span}(v_1, \dots, v_m)$.
















