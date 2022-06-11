---
title: "Exercise 1A Problem 5"
date: 2022-06-08T21:13:55+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 5 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $(\alpha + \beta) + \lambda = \alpha + (\beta + \lambda)$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

## Solution
Let $\alpha = a + bi$, $\beta = c + di$ and $\lambda = e + fi$. Then by the associativity
of real numbers:
$$(\alpha + \beta) + \lambda = \left((a + bi) + (c + di)\right) + (e + fi)$$
$$\stackrel{D1.1}{=} ((a + c) + (b + d)i) + (e + fi) \stackrel{D1.1}{=} ((a + c) + e) + ((b + d) + f)i$$
$$= (a + (c + e)) + (b + (d + f))i \stackrel{D1.1}{=} (a + bi) + ((c + e) + (d + f)i)$$
$$= \alpha + (\beta + \lambda)$$
Proving the associativity complex numbers under addition.









