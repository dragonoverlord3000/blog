---
title: "Exercise 2C Problem 16"
date: 2022-06-27T19:37:59+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 16 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U_1, \dots, U_m$ are finite-dimensional subspaces of $V$ such that $U_1 + \dots + U_m$ is a direct sum. Prove that $U_1 \oplus \dots \oplus U_m$ is finite-dimensional and
$$\dim (U_1 \oplus \dots \oplus U_m) = \dim U_1 + \dots + \dim U_m$$

## Solution
Proceed by induction on $m$

> BC: for $m = 1$ we have $\dim U_1 = \dim U_1$

> IH: suppose that it holds for some $m = k \in \mathbb{N}$ that $\dim (U_1 \oplus \dots \oplus U_k) = \dim U_1 + \dots + \dim U_k$

> IS: then it follows that:
$$\dim (U_1 \oplus \dots \oplus U_k \oplus U_{k+1}) \stackrel{T2.43}{=} \dim (U_1 \oplus \dots \oplus U_k) + \dim U_{k+1}$$
$$- \dim(U_1 \oplus \dots \oplus U_k) \cap U_{k+1} \stackrel{\spadesuit}{=} \dim (U_1 \oplus \dots \oplus U_k) + \dim U_{k+1}$$
$$\stackrel{IH}{=} \dim U_1 + \dots + \dim U_k + \dim U_{k+1}$$
Where $\spadesuit$ is due to $U_1 \oplus \dots \oplus U_k \oplus U_{k+1}$ being a direct sum.

