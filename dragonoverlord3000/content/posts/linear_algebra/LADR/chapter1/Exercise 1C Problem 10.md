---
title: "Exercise 1C Problem 10"
date: 2022-06-16T05:52:27+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 10 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U_1$ and $U_2$ are subspaces of $V$. Prove that the intersection $U_1 \cap U_2$ is a subspace of $V$.

## Solution
1. $U_1$ and $U_2$ are subspaces and therefore $0 \in U_1$ and $0 \in U_2$ implying that $0 \in U_1 \cap U_2$.
2. If $x,y \in U_1 \cap U_2$, then $x + y \in U_1$ and $x + y \in U_2$ because these are subspaces. Therefore $x + y \in U_1 \cap U_2$ implying that $U_1 \cap U_2$ is closed under addition.
3. Similarly if $\lambda \in \mathbb{F}$, then $\lambda x \in U_1$ and $\lambda x \in U_2$ because $U_1$ and $U_2$ are subspaces and $x \in U_1 \cap U_2$, implying that $\lambda x \in U_1 \cap U_2$. Therefore $U_1 \cap U_2$ is closed under scalar multiplication.













