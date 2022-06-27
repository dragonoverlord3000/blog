---
title: "Exercise 2C Problem 4"
date: 2022-06-27T10:23:58+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U = \lbrace p \in \mathcal{P}_4(\mathbb{F}) | p(6) = 0 \rbrace$. Find a basis of $U$

(b) Extend the basis in part (a) to a basis of $\mathcal{P}_4(\mathbb{F})$

(c) Find a subspace $W$ of $\mathcal{P}_4(\mathbb{F})$ such that $\mathcal{P}_4(\mathbb{F}) = U \oplus W$

## Solution
> (a) It's clear that $U$ is a proper subspace of $V$ i.e. $\dim U < \dim \mathcal{P}_4(\mathbb{F})$, as there are vectors in $\mathcal{P}_4(\mathbb{F})$ that are not in $U$ e.g. $p(z) = z$. 
Moreover, following the process described in example 2.41, we see that the vectors $z-6,(z - 6)^2, (z - 6)^3, (z - 6)^4$ are all linearly independent and since they're all in $U$. Therefore (by using $\dim U < \dim \mathcal{P}_4(\mathbb{F}) = 5$) we must have that the list $z-6,(z - 6)^2, (z - 6)^3, (z - 6)^4$ is a basis of $U$ as per theorem 2.29.

> (b) As $p(z) = 1$ $\cancel{\in}$ $U$, the list  $1,z-6,(z - 6)^2, (z - 6)^3, (z - 6)^4$ is therefore a linearly independent list, by [P2A11](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-11/), of length 5. Theorem 2.39 implies that it is a basis for $\mathcal{P}_4(\mathbb{F})$.

> (c) Let $W = \textrm{span}(1)$, then by (b) we must have $U \oplus W = \mathcal{P}_4(\mathbb{F})$















