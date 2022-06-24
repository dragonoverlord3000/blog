---
title: "Exercise 1C Problem 14"
date: 2022-06-23T17:20:51+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 14 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Verify the assertion in Example 1.38

## Solution
By directly applying the definition of sums of subspaces we obtain:
$$U + W \stackrel{D1.36}{=} \lbrace (x_1, x_1, y_1, y_1) + (x_2, x_2, x_2, y_2) | x_1,y_1,x_2,y_2 \in \mathbb{F} \rbrace \stackrel{D1.12}{=} \lbrace (x_1 + x_2, x_1 + x_2, y_1 + x_2, y_1 + y_2) | x_1,y_1,x_2,y_2\rbrace$$
Now let $x = x_1 + x_2$, $y = x_1 + y_2$ and $z = y_1 + y_2$ (notice that the right hand side does not put any constraints on $x,y,z$ as each equation above has a variable that is not in any of the other equations e.g. $x_2$ is only in the definition of $x$, not $y$ or $z$), thus our final subspace becomes:
$$U + W = \lbrace (x,x,y,z) | x,y,z \in \mathbb{F} \rbrace$$

