---
title: "Exercise 2C Problem 12"
date: 2022-06-27T18:38:04+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 12 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U$ and $W$ are both five-dimensional subspaces of $\mathbb{R}^9$. Prove that $U \cap W \neq \lbrace 0 \rbrace$


## Solution
By theorem 2.43, 2.38 and the fact that $U + W$ is a subspace of $\mathbb{R}^9$ by theorem 1.39:
$$9 = \dim \mathbb{R}^9 \geq \dim (U + W) = \dim U + \dim W - \dim U \cap W$$
$$= 5 + 5 - \dim U \cap W$$
Implying that $\dim U \cap W \geq 1$.





