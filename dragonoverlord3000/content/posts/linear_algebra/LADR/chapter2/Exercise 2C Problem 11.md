---
title: "Exercise 2C Problem 11"
date: 2022-06-27T17:45:32+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose that $U$ and $W$ are subspaces of $\mathbb{R}^{8}$ such that $\dim U = 3$, $\dim W = 5$, and $U + W = \mathbb{R}^{8}$. Prove that $\mathbb{R}^8 = U \oplus W$


## Solution
By theorem 2.43 we have: 
$$8 = \dim \mathbb{R}^{8} = \dim(U + W) $$
$$= \dim U + \dim W - \dim (U_1 \cap U_2)$$
$$= 3 + 5 - \dim(U \cap W)$$
Implying that $\dim(U \cap W) = 0$, which in turn implies $U \cap W = \lbrace 0 \rbrace$. 





