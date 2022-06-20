---
title: "Exercise 1C Problem 8"
date: 2022-06-15T20:38:01+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Give an example of a nonempty subset $U$ of $\mathbb{R}^2$ such that $U$ is closed under scalar multiplication, but $U$ is not a subspace of $\mathbb{R}^2$.

## Solution
With inspiration from [problem 6](google.com) we construct the following subset of $\mathbb{R}^2$: $\lbrace (x,y) \in \mathbb{R}^2 | x^2 = y^2 \rbrace$.
Then if $(x,y)$ is in the subset $\lambda (x,y) = (\lambda x, \lambda y)$ has the property that $(\lambda x)^2 = \lambda^2 (x^2) = \lambda^2 (y^2) = (\lambda y)^2$, that is - the subset is closed under scalar multiplication.

However $(-1,1)$ and $(1,1)$ are both in the subset because $(-1)^2 = 1^2$, but $(-1,1) + (1,1) = (0,2)$ is not in the subset because $0^2 \neq 2^2$, therefore the constructed subset of $\mathbb{R}^2$ is not closed under addition and is therefore not a subspace of $\mathbb{R}^2$.



