---
title: "Exercise 2C Problem 7"
date: 2022-06-27T12:20:34+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U = \lbrace p \in \mathcal{P}_4(\mathbb{F}) | p(2) = p(5) = p(6) \rbrace$. Find a basis of $U$

(b) Extend the basis in part (a) to a basis of $\mathcal{P}_4(\mathbb{F})$

(c) Find a subspace $W$ of $\mathcal{P}_4(\mathbb{F})$ such that $\mathcal{P}_4(\mathbb{F}) = U \oplus W$


## Solution
> (a) $U$ is a subspace of $U^\prime = \lbrace p \in \mathcal{P}_4(\mathbb{F}) | p(2) = p(5) \rbrace$, as any vector in $U$ is also in $U^\prime$. Because $(z - 2)(z - 5)$ is in $U^\prime$ and not in $U$, we must have $\dim U < \dim U^\prime = 4$, see [P2C6](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2c-problem-6/). The linearly independent list $1, (z-2)(z-5)(z-6), z(z-2)(z-5)(z-6)$ is therefore a basis for $U$ by theorem 2.39

> (b) As $(z - 2)(z - 5) \in U^\prime$ and $(z - 2)(z - 5)$ $\cancel{\in}$ $U$, we can extend the list $1, (z-2)(z-5)(z-6), z(z-2)(z-5)(z-6)$ to a basis of $U^\prime$ by appending $(z - 2)(z - 5)$ to the list. Then by [P2C6](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2c-problem-6/) we can extend this basis of $U^\prime$ to a basis of $\mathcal{P}_4(\mathbb{F})$ by appending $z$ to the list. Therefore the list $1, (z-2)(z-5)(z-6), z(z-2)(z-5)(z-6), (z - 2)(z - 5), z$ is therefore a basis of $\mathcal{P}_4(\mathbb{F})$.

> (c) Let $W = \textrm{span}(z, (z-2)(z-5))$, then by (b) we must have $W \oplus U = \mathcal{P}_4(\mathbb{F})$.












