---
title: "Exercise 1C Problem 2"
date: 2022-06-13T06:42:44+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Verify all assertions in Example 1.35

## Solution
### Subspace (a)
$(\leftarrow)$ { $(x_1, x_2, x_3, x_4) \in \mathbb{F}^4 | x_3 = 5x_4 + b $ } is a subspace, then $(0,0,0,0) = 0$ is an element of this subspace by theorem 1.34, which implies $0 = x_3 = 5x_4 + b = 5\cdot 0 + b = b$. 

$(\rightarrow)$ $b = 0$, then:
1. $0 = (0,0,0,0)$ satisfies the condition $x_3 = 5x_4 + b$ because $x_3 = 0 = 5 \cdot 0 + 0 = 5x_4 + b$, and is therefore in the subset.
2. The subset is closed under addition, since given $x = (x_1, x_2, x_3, x_4)$ and $y = (y_1, y_2, y_3, y_4)$ in the subset, we must have that $x + y \stackrel{D1.12}{=} (x_1 + y_1, x_2 + y_2, x_3 + y_3, x_4 + y_4)$ with $(x_3 + y_3) = 5x_4 + 5y_4 \stackrel{P1A9}{=} 5(x_4 + y_4)$, implying that $x + y$ is also in the subset.
3. Moreover, for all $\lambda \in \mathbb{F}$ we have $\lambda x \stackrel{D1.17}{=} (\lambda x_1, \lambda x_2, \lambda x_3, \lambda x_4)$ with $\lambda x_3 = \lambda (5x_4) \stackrel{P1A6 \land E1.14}{=} 5 (\lambda x_4)$, thus the set is closed under scalar multiplication.


### Subspace (b)
1. The zero function $0(x) = 0$ is in the subset.
2. The sum of two real valued functions on $[0,1]$ is a new real valued function on $[0,1]$ and is thus in the subset.
3. Multiplying a real valued function on $[0,1]$ by some $\lambda \in \mathbb{R}$ results in a new real valued function on $[0,1]$ and is thus in the subset.


### Subspace (c)
1. The zero function $0(x) = 0$ is in the subset.
2. The sum of two differentiable functions on $\mathbb{R}$ is a new differentiable function on $\mathbb{R}$ and is thus in the subset.
3. Multiplying a differentiable function on $\mathbb{R}$ by some $\lambda \in \mathbb{R}$ results in a new differentiable function on $\mathbb{R}$ and is thus in the subset.


### Subspace (d)
$(\leftarrow)$ if $0(x) = 0$ is the additive identity in $\mathbb{R}^{(0,3)}$, and must therefore also be in the given *subspace* of $\mathbb{R}^{(0,3)}$, but $b = 0^\prime(x) = 0$, thus $b = 0$.

$(\rightarrow)$ $b = 0$, then:
1. The zero function $0(x) = 0$ is in the subset.
2. Let $f,g \in \mathbb{R}^{(0,3)}$ with $f^\prime(2) = g^\prime(2) = b = 0$, then $0 = 0 + 0 = f^\prime(2) + g^\prime(2) = (f + g)^\prime(2)$ by the linearity of the derivative.
3. For all $\lambda \in \mathbb{R}$ we must have that $\lambda f(x) \in \mathbb{R}^{(0,3)}$ - see *subspace (c)* - and $0 = \lambda 0 = \lambda f^\prime(2)$, therefore subset (d) is closed under scalar multiplication.

### Subspace (e)
Let ${x_n}$ and ${y_n}$ be complex sequences with limit $0$, then
1. Clearly the zero-sequence ${0}$ is in the subset.
2. ${x_n} + {y_n}$ is a complex sequence with limit $0 + 0 = 0$, thus subset (e) is closed
under addition.
3. ${\lambda x_n}$ is a complex sequence with limit $\lambda 0 = 0$ for all $\lambda \in \mathbb{C}$, thus subset (e) is closed under scalar multiplication.



