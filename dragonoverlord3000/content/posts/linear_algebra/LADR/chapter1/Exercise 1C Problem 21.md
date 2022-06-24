---
title: "Exercise 1C Problem 21"
date: 2022-06-24T15:17:33+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 21 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose 
$$U = \lbrace (x,y,x+y,x-y,2x) \in \mathbb{F}^5 | x,y \in \mathbb{F} \rbrace$$
Find a subspace $W$ of $\mathbb{F}^5$ such that $\mathbb{F}^5 = U \oplus W$

## Solution
Let $W = \lbrace (0,0,x,y,z) \in \mathbb{F}^5 |x,y,z \in \mathbb{F} \rbrace$, then $U + W = \lbrace (x_1, x_2, x_3, x_4, x_5) \in \mathbb{F}^5 | x_1,x_2,x_3,x_4,x_5 \in \mathbb{F} \rbrace = \mathbb{F}^5$. Also 
$$U \cap W = \lbrace u \in \mathbb{F}^5 | u \in U \land u \in W \rbrace$$
But $(x_1,x_2,x_3,x_4,x_5) = u \in U$ implies that if $x_1 = x_2 = 0$ and $(x_1,x_2,x_3,x_4,x_5)$ $= u \in W$ implies that $x_3 = x_1 + x_2$, $x_4 = x_1 - x_2$ and $x_5 = 2x_1$, but $x_1 = x_2 = 0$ then implies $x_1 = x_2 = x_3 = x_4 = x_5 = 0$, thus $U \cap W = \lbrace 0 \rbrace$ implying that $U \oplus W = \mathbb{F}^5$.







