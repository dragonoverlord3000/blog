---
title: "Exercise 2C Problem 15"
date: 2022-06-27T19:18:43+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 15 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $V$ is finite-dimensional, with $\dim V = n \geq 1$. Prove that there exist 1-dimensional subspaces $U_1, \dots, U_n$ of $V$ such that
$$V = U_1 \oplus \dots \oplus U_n$$

## Solution
Let $u_1, \dots, u_n$ be a basis of $V$, then $U_i = \textrm{span}(u_i)$ has the property that $\sum_{i=1}^{j}U_i \cap U_{j+1} = \lbrace 0 \rbrace$ for all $j \in \lbrace 1,2, \dots, n-1 \rbrace$ by the linear independence of $u_1, \dots, u_n$ and also $U_1 + \dots + U_n \stackrel{D1.36 \land D2.5}{=} \textrm{span}(u_1, \dots, u_n) = V$ by the fact that $u_1, \dots, u_n$ is a spanning list by definition 2.27.








