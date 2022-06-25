---
title: "Exercise 2A Problem 5"
date: 2022-06-25T18:19:07+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 5 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
> *(a)* Show that if we think of $\mathbb{C}$ as a vector space over $\mathbb{R}$, then the list $(1 + i, 1 - i)$ linearly independent.

> *(b)* Show that if we think of $\mathbb{C}$ as a vector space over $\mathbb{C}$, then the list $(1 + i, 1 - i)$ linearly dependent.

## Solution
*(a)* if we let $x,y \in \mathbb{R}$, then
$$0 + 0i = 0 = x(1 + i) + y(1 - i) \stackrel{P1A6 \land D1.1}{=} x + y + (x - y)i$$
By equating coefficients we see that $x + y = x - y = 0$, from which it follows that $x = y = 0$, thus $(1 + i, 1 - i)$ is linearly independent.

*(b)* if we let $x,y \in \mathbb{C}$ we see that $x = i$, $y = 1$ is a non-trivial linear combination of the given vectors that equate to $0$:
$$x(1 + i) + y(1 - i) = i - 1 + 1 - i = 0$$
Therefore, by definition 2.19, the given list is linearly dependent.

