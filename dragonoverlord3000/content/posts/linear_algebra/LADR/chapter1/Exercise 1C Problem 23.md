---
title: "Exercise 1C Problem 23"
date: 2022-06-24T15:44:00+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 23 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove or give counterexample: if $U_1$, $U_2$, $W$ are subspaces of $V$ such that
$$U_1 \oplus W = U_2 \oplus W$$
then $U_1 = U_2$

## Solution
We have that $U_1 \oplus W = V = U_2 \oplus W$, therefore $U_1 \cap W = U_2 \cap W = \lbrace 0 \rbrace$. Choosing any element $u \in U_1$ will therefore not be in $W$, but will be in $V$ as $U_1 \subseteq V$.

Since $u$ $\cancel{\in}$ $W$ and since $u \in V = U_2 \oplus W$ we must have that $u \in U_2$, and by a similar argument $u \in U_2$ implies $u \in U_1$. Therefore $U_1 \subseteq U_2$ and $U_1 \subseteq U_2$ and thus $U_1 = U_2$.









