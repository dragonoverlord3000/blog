---
title: "Exercise 1C Problem 3"
date: 2022-06-13T18:59:54+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that the set of differentiable real-valued functions $f$ on the interval $(-4,4)$ such that $f^\prime(-1) = 3f(2)$ is a subspace of $\mathbb{R}^{(-4,4)}$

## Solution
1. The zero-function $0(x) = 0$ is in the set, since $0 = \frac{d}{dt}0 = \frac{d}{dt}0(x) = 0^\prime(x)$ from which it follows that $0^\prime(-1) = 0 = 3 \cdot 0 = 3 \cdot 0(2)$
2. If $f$ and $g$ are in the subset, then $h(x) = f(x) + g(x)$ has the property that $h^\prime(x) = \frac{d}{dx}(f(x) + g(x)) = f^\prime(x) + g^\prime(x)$ and thus $h^\prime(-1) = f^\prime(-1) + g^\prime(-1) = 3f(2) + 3g(2) = 3(g + f)(2) = 3h(2)$ and thus $h(x)$ is in the subset. Therefore the subset is closed under addition.
3. Now take $\lambda \in \mathbb{R}$, then let $h(x) = \lambda f(x)$, then $h^\prime(x) = \frac{d}{dt}\lambda f(x) = \lambda \frac{d}{dt}f(x) = \lambda f^\prime(x)$ and therefore $h^\prime(-1) = \lambda f^\prime(-1) = \lambda 3f(2) = 3 (\lambda f)(2) = 3h(2)$, thus the subset is closed under scalar multiplication.

