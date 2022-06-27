---
title: "Exercise 2C Problem 2"
date: 2022-06-26T17:23:00+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that the subspaces of $\mathbb{R}^2$ are precisely $\lbrace 0 \rbrace, \mathbb{R}^2$, and all lines through the origin.

## Solution
As per theorem 2.38, we must have that any subspace $U$ of $R^2$ has a basis of length $0$, $1$ or $2$. The case when a basis of $U$ has length $0$ is exactly when $U = \lbrace 0 \rbrace$, when $\dim U = 2 = \dim \mathbb{R}^2$ we must have $U = \mathbb{R}^2$ by [P2C1](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2c-problem-1/). 

When $\dim U = 1$, a basis of $U$ consist of a single element $v = (x,y)$ in $\mathbb{R}^2$, for $x,y \in \mathbb{R}$, implying that $U = \textrm{span}((x,y))$ i.e. $U$ is the set of all vectors that can be written as $\lambda (x,y)$ for $\lambda \in \mathbb{R}$. This is exactly all lines through the origin.








