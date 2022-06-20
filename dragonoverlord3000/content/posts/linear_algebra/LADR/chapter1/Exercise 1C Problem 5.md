---
title: "Exercise 1C Problem 5"
date: 2022-06-15T17:31:50+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 5 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Is $\mathbb{R}^2$ a subspace of the complex vector space $\mathbb{C}^2$?

## Solution
No, $\mathbb{R}^2$ is not a subspace of $\mathbb{C}^2$ - a subspace has the same addition and scalar multiplication as the space it's a subspace of - see definition 1.32. But $\mathbb{C}^2$ is a vector space over $\mathbb{C}$, thus for any scalar $\lambda \in \mathbb{C}$ any vector $v$ of our subset $\mathbb{R}^2$ should satisfy $\lambda v \in \mathbb{R}^2$, but for $\lambda = i$, this is clearly not the case - take e.g. $(1,0) \in \mathbb{R}^2$, then $i \cdot (1,0) \; \cancel{\in} \; \mathbb{R}^2$ and $\mathbb{R}^2$ is thus not a subspace of $\mathbb{C}^2$.



