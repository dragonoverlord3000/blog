---
title: "Exercise 2A Problem 3"
date: 2022-06-25T17:49:29+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Find a number $t$ such that 
$$(3,1,4), (2,-3,5), (5,9,t)$$
is not linearly independent in $\mathbb{R}^3$

## Solution
If we want the given list to be linearly dependent, then we want to find $x,y \in \mathbb{R}$ such that:
$$x(3,1,4) + y(2,-3,5) = (5,9,t)$$
From the first two coordinates we see that $3x + 2y = 5$ and $x - 3y = 9$. By adding $-3$ times the second equation to the first, we see that $11y = -22$ i.e. $y = -2$ and the second equation then implies $x = 3$. Therefore, from the third coordinates of the vectors above, we want $t = 4x + 5y = 4 \cdot 3 - 5 \cdot 2 = 2$. Thus $t = 2$ is the only $t$ that will make the given list linearly dependent.












