---
title: "Exercise 2C Problem 3"
date: 2022-06-26T17:53:19+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that the subspaces of $\mathbb{R}^3$ are precisely $\lbrace 0 \rbrace$, $\mathbb{R}^3$, all lines in $\mathbb{R}^3$ through the origin, and all planes in $\mathbb{R}^3$ through the origin.

## Solution
As per theorem 2.38, we must have that any subspace $U$ of $R^3$ has a basis of length $0$, $1$, $2$ or $3$. The cases $\dim U = 0$ and $\dim U = 3$ are precisely the cases when $U = \lbrace 0 \rbrace$ and $U = \mathbb{R}^3$ respectively - as per [P2B1](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2b-problem-1/) and [P2C1](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2c-problem-1/).

The case when $\dim U = 1$ is exactly when $\dim U = \textrm{span}(v)$ for some $v = (x^\prime,y^\prime,z^\prime) \in \mathbb{R}^3$. This is because $\dim U = 1$ implies that a basis for $U$ has length 1 and any non-zero $v \in U \subseteq \mathbb{R}^3$ is therefore a basis for $U$ as per example 2.18 (a) plus theorem 2.39. And because $(x,y,z) = \lambda (x^\prime,y^\prime,z^\prime)$ for $\lambda \in \mathbb{R}$ is exactly the parametric equation for a line in $\mathbb{R}^3$ through the origin $U$ is all lines through the origin when $\dim U = 1$.

Similarly, when $\dim U = 2$ we have two linearly independent vectors $v = (x_1,y_1,z_1),u = (x_2,y_2,z_2)$ in $\mathbb{R}^3$ as a basis, implying that $U = \textrm{span}(v_1,v_2)$ which can be expressed as all triples $(x,y,z)$ such that $(x,y,z) = \lambda (x_1, y_1, z_1) + \mu (x_2, y_2,z_2)$ for $\lambda, \mu \in \mathbb{R}$. 
This is exactly the parametric form for all planes in $\mathbb{R}^3$ through the origin.







