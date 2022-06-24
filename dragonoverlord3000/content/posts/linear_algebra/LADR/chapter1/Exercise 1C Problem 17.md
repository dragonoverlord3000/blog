---
title: "Exercise 1C Problem 17"
date: 2022-06-24T09:09:20+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 17 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Is the operation of addition on the subspaces of $V$ associative? In other words, if $U_1, U_2, U_3$ are subspaces of $V$, is
$$(U_1 + U_2) + U_3 = U_1 + (U_2 + U_3) ?$$

## Solution
Yes, *Proof*:
$$(U_1 + U_2) + U_3 \stackrel{D1.36}{=} \lbrace u_1 + u_2 | u_1 \in U_1, u_2 \in U_2 \rbrace + U_3$$
$$\stackrel{D1.36 \land D1.39}{=} \lbrace (u_1 + u_2) + u_3 | u_1 \in U_1, u_2 \in U_2, u_3 \in U_3 \rbrace$$
$$\stackrel{D1.19 \land D1.39}{=} \lbrace u_1 + (u_2 + u_3) | u_1 \in U_1, u_2 \in U_2, u_3 \in U_3\rbrace$$
$$\stackrel{D1.36 \land D1.39}{=} U_1 + \lbrace u_2 + u_3 | u_2 \in U_2, u_3 \in U_3 \rbrace \stackrel{D1.36}{=} U_1 + (U_2 + U_3)$$



