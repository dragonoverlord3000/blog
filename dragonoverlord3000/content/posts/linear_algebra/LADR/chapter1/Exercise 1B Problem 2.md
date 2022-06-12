---
title: "Exercise 1B Problem 2"
date: 2022-06-12T17:26:41+02:00
description: "Linear Algebra Done Right - Exercise 1B Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Suppose $a \in \mathbb{F}, v \in V$, and $av = 0$. Prove $a = 0$ or $v = 0$

## Solution
First suppose $a \neq 0$, then:
$$0 \stackrel{T1.30}{=} \frac{1}{a}0 = \frac{1}{a}(av) \stackrel{P1A13}{=} \left(\frac{1}{a} \cdot a\right)v = 1v \stackrel{D1.19}{=} v$$
Now suppose $v \neq 0$, then any vector $u \in V$ can be written as $w + v$ for $w \in V$,
since $w = u - v \to u = w + v$, but then:
$$au = a(w + v) \stackrel{D1.19}{=} aw + av = aw \to a = 0 \lor u = w = u - v$$
The latter of these cases, implies $v = 0$ which is a contradiction, thus $a = 0$.




