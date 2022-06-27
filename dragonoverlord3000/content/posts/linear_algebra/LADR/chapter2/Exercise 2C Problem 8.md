---
title: "Exercise 2C Problem 8"
date: 2022-06-27T13:02:14+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U = \lbrace p \in \mathcal{P}_4(\mathbb{F}) | \int_x^y p = 0 \land -x=y=1\rbrace$. Find a basis of $U$

(b) Extend the basis in part (a) to a basis of $\mathcal{P}_4(\mathbb{F})$

(c) Find a subspace $W$ of $\mathcal{P}_4(\mathbb{F})$ such that $\mathcal{P}_4(\mathbb{F}) = U \oplus W$


## Solution
> (a) It's clear that none of the vectors in the linearly independent list $1, z^2, z^4$ are in $U$, therefore by theorem 2.33 we must have $\dim U \leq \dim \mathcal{P}_4(\mathbb{F}) - 3 = 2$. As the list $z, z^3$ is linearly independent and both vectors are in $U$ we must therefore have that $z, z^3$ must be a basis of $U$ by theorem 2.39.

> (b) Applying theorem 2.33 with $u_1 = z, u_2 = z^3$ and $w_i = z^{i-1}$ for $i \in \lbrace 1,2,3,4,5 \rbrace$, we get the basis $1,z,z^2,z^3,z^4$ for $U$.

> (c) Let $W = \textrm{span}(1,z^2,z^3)$, then by (b) and the linearity of the integral operator, we must have $\mathcal{P}_4(\mathbb{F}) = U \oplus W$.




