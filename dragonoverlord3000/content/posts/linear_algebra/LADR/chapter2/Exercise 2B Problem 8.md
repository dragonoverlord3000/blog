---
title: "Exercise 2B Problem 8"
date: 2022-06-26T16:12:43+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U$ and $W$ are subspaces of $V$ such that $V = U \oplus W$. Suppose also that $u_1, \dots, u_m$ is a basis of $U$ and $w_1, \dots, w_n$ is a basis of $W$. Prove that
$$u_1, \dots, u_m, w_1, \dots, w_n$$
is a basis of $V$

## Solution
Every vector in $V$ can be written uniquely as a vector $u \in U$ plus a vector $w \in W$ as per the fact that $V = U \oplus W$. Therefore if $v \in V$, then for a specific $u \in U$ and $w \in W$ we have $v = u + w$.

Since $u_1, \dots, u_m$ is a basis for $U$ any vector $u \in U$ can be written uniquely in terms of this basis as per theorem 2.29 and similarly for any $w \in W$. Therefore $v = u + w$ is uniquely determined in the list $u_1, \dots, u_m, w_1, \dots, w_n$ which by theorem 2.29 implies that $u_1, \dots, u_m, w_1, \dots, w_n$ is a basis for $V$.













