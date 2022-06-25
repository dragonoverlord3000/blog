---
title: "Exercise 2A Problem 4"
date: 2022-06-25T18:00:51+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Verify the assertion in the second bullet point in Example 2.20

## Solution
$(\leftarrow)$ This is bullet point number 1

$(\rightarrow)$ If $(2,3,1), (1,-1,2), (7,3,c)$ is linearly dependent, then by definition 2.19 there must exist $x,y \in \mathbb{F}^3$ such that:
$$x(2,3,1) + y(1,-1,2) = (7,3,c)$$
From the first and second coordinates above, we see that $2x + y = 7$ and $3x - y = 3$. Adding these we get $5x = 10$ i.e. $x = 2$, which by equation one implies $y = 7 - 2x = 3$, thus $c = x + 2y = 2 + 2 \cdot 3 = 8$.










