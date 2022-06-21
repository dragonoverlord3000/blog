---
title: "Exercise 1C Problem 11"
date: 2022-06-17T05:50:52+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove that the intersection of every collection of subspaces of $V$ is a subspace of $V$

## Solution
Let $U_1, U_2, \dots, U_k$ be a collection of subspaces in $V$, then:
1. $0 \in \bigcap_{i=1}^{k} U_i$ because $U_1, U_2, \dots, U_k$ are all subspaces i.e. they all contain $0$.
2. Let $v,u \in \bigcap_{i=1}^{k} U_i$, then $v + u \in \bigcap_{i=1}^{k} U_i$ because $v,u \in U_1 \to v + u \in U_1$, $v,u \in U_2 \to v + u \in U_2$, $\dots$, $v,u \in U_k \to v + u \in U_k$, by the fact that $U_1, U_2, \dots, U_k$ are all subspaces. Therefore $\bigcap_{i=1}^{k}$ is closed under addition.
3. Let now $\lambda \in \mathbb{F}$, then $\lambda v \in \bigcap_{i=1}^{k} U_i$ because $U_1, U_2, \dots, U_k$ are all subspaces and $v \in U_1$, $v \in U_2$, $\dots$, $v \in U_k$. Thus $\bigcap_{i=1}^{k}$ is closed under scalar multiplication.



