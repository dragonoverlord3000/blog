---
title: "Exercise 1C Problem 7"
date: 2022-06-15T18:28:32+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Give an example of a nonempty subset $U$ of $\mathbb{R}^2$ such that $U$ is closed
under addition and under taking additive inverses (meaning $-u \in U$
whenever $u \in U$), but $U$ is not a subspace of $\mathbb{R}^2$.

## Solution
Consider $U^2 = \mathbb{Z}^2$, this is clearly a subset of $\mathbb{R}^2$ and is also closed under addition: $a, b \in \mathbb{Z}^2$ implies $a + b \in \mathbb{Z}^2$, also $a \in \mathbb{Z}^2 \to -a \in \mathbb{Z}^2$ since $\mathbb{Z}$ is closed under addition and negation. 

But $\mathbb{Z}^2$ is not a subspace over $\mathbb{R}$ since $(1,1) \in \mathbb{Z}^2$, but $\frac{1}{2} (1,1)$ $ \cancel{\in} $ $ \mathbb{Z}^2$. That is, $\mathbb{Z}^2$ is not closed under multiplication by real scalars and is therefore not a subspace of $\mathbb{R}^2$.

