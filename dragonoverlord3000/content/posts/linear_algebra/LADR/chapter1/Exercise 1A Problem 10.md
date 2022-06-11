---
title: "Exercise 1A Problem 10"
date: 2022-06-09T15:33:49+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 10 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Find $x \in \mathbb{R}^4$ such that
$$(4, -3, 1, 7) + 2x = (5, 9, -6, 8)$$

## Solution
First isolate $2x$ by subtracting the leftmost vector from both sides of the equation which can be done by applying D1.12, D1.16 and D1.17:
$$2x = (5, 9, -6, 8) - (4, -3, 1, 7) = (1, 12, -7, 1)$$
Then divide by $2$ on both sides of the equation:
$$x = \left(1/2, 6, -7/2, 1/2\right)$$
This is the solution.


