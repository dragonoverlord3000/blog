---
title: "Exercise 1C Problem 4"
date: 2022-06-15T15:52:49+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Suppose $b \in \mathbb{R}$. Show that the set of continuous real-valued functions $f$ on the interval $[0,1]$ such that $\int_0^1 f = b$ is a subspace of $\mathbb{R}^{[0,1]}$ if and only if $b = 0$.

## Solution
$(\leftarrow)$ given that the zero-function $0(x) = 0$ has to be in the set for it to be a subspace $b = \int_0^1 0(x)dx = 0$ since $\int_0^1 f = b$ for all $f$ including when $f(x) = 0(x)$

$(\rightarrow)$ $b = 0$, then:
1. The zero-function satisfies $\int_0^1 0(x)dx = 0 = b$ and is thus in the subset.
2. Let $f$ and $g$ be in the subset, then $\int_0^1 (f + g)(x)dx = \int_0^1 f(x) + g(x)dx = \int_0^1 f(x)dx + \int_0^1 g(x)dx = b + b = 0 + 0 = 0 = b$, thus the subset is closed under addition.
3. Let $\lambda \in \mathbb{R}$, then for any function $f$ in the subset we must have $\int_0^1 (\lambda f)(x)dx = \lambda \int_0^1 f(x) = \lambda \cdot 0 = 0 = b$, thus the subset is closed under scalar multiplication.





