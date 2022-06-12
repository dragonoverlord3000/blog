---
title: "Exercise 1B Problem 5"
date: 2022-06-12T18:09:20+02:00
description: "Linear Algebra Done Right - Exercise 1B Problem 5 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Show that in the definition of a vector space (1.19), the additive inverse condition can be replaced with the condition that 
$$0v = 0 \textrm{ for all } v \in V$$
Here the $0$ on the left side is the number $0$, and the $0$ on the right side is
the additive identity of $V$

## Solution
Let $v,w \in V$, such then:
$$0 = 0v = (1 + (-1))v \stackrel{D1.19}{=} 1v + (-1)v$$
Now define $-v$ to equal $(-1)v$ and we see that any $v \in V$ has an additive inverse.

