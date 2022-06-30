---
title: "Exercise 3A Problem 1"
date: 2022-06-27T21:51:20+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 1 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $b,c \in \mathbb{R}$. Define $T: \mathbb{R}^3 \to \mathbb{R}^2$ by 
$$T(x,y,z) = (2x - 4y + 3z + b, 6x + cxyz)$$
Show that $T$ is linear if and only if $b = c = 0$

## Solution
$(\rightarrow)$ By theorem 3.11 we have $T0 = 0$, therefore $(0,0) = T(0,0,0) = (b,0)$ implying $b = 0$.
Use additivity of $T$ and $b = 0$ as such:
$$(1,6+c) = T(1,1,1) = T((1,0,0) + (0,1,1))$$ 
$$\stackrel{D3.2}{=} T(1,0,0) + T(0,1,1) = (2,6) + (-1,0) \stackrel{D1.12}{=} (1,6)$$
Implying $6 + c = 6$ or equivalentely $c = 0$.

$(\leftarrow)$ is implied by the last example in Example 3.4.





