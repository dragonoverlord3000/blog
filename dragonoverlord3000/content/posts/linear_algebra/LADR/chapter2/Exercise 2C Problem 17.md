---
title: "Exercise 2C Problem 17"
date: 2022-06-27T20:01:42+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 17 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
You might guess, by analogy with the formula for the number of elements in the union of three subsets of a finite set, that if $U_1, U_2, U_3$ are subspaces of a finite-dimensional vector space, then
$$\dim(U_1 + U_2 + U_3) = \dim U_1 + \dim U_2 + \dim U_3$$
$$- \dim (U_1 \cap U_2) - \dim(U_1 \cap U_3) - \dim(U_2 \cap U_3)$$
$$+ \dim(U_1 \cap U_2 \cap U_3)$$
Prove this or give a counterexample.

## Solution
Let $V = \mathbb{R}^3$ and $U_1 = \textrm{span}((1,0,0))$, $U_2 = \textrm{span}((0,1,0))$ and $U_3 = \textrm{span}((1,1,0))$. Then:
$$2 = \dim (U_1 + U_2 + U_3) = \dim U_1 + \dim U_2 + \dim U_3 - \dim (U_1 \cap U_2) - \dim(U_1 \cap U_3)$$ 
$$- \dim(U_2 \cap U_3) + \dim(U_1 \cap U_2 \cap U_3) = 1 + 1 + 1 - 0 - 0 - 0 + 0 = 3$$
A contradiction.






