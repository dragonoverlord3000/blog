---
title: "Exercise 2C Problem 14"
date: 2022-06-27T18:57:01+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 14 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U_1, \dots, U_m$ are finite-dimensional subspaces $V$. Prove that $U_1 + \dots + U_m$ is finite-dimensional and
$$\dim (U_1 + \dots + U_m) \leq \dim U_1 + \dots + \dim U_m$$

## Solution
Theorem 1.39 implies that $U_1 + \dots + U_m$ is a subspace of $V$ and theorem 2.26 therefore ensure that $U_1 + \dots + U_m$ is finite dimensional.

To prove the second part:
$$\dim U_1 + \dots + U_{m-1} + U_m \stackrel{T2.43}{=} \dim (U_1 + \dots + \dim U_{m-1})+ \dim U_m $$
$$- \dim (U_1 + \dots + U_{m-1}) \cap U_m \stackrel{\spadesuit}{\leq} \dim U_1 + \dots + \dim U_{m-1} + \dim U_m$$
Where $\spadesuit$ is due to $\dim U \geq 0$ for all subspaces $U$ - see the infobox on page 19.













