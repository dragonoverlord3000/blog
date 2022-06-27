---
title: "Exercise 2C Problem 6"
date: 2022-06-27T11:56:25+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
(a) Let $U = \lbrace p \in \mathcal{P}_4(\mathbb{F}) | p(2) = p(5) \rbrace$. Find a basis of $U$

(b) Extend the basis in part (a) to a basis of $\mathcal{P}_4(\mathbb{F})$

(c) Find a subspace $W$ of $\mathcal{P}_4(\mathbb{F})$ such that $\mathcal{P}_4(\mathbb{F}) = U \oplus W$

## Solution
> (a) As $z$ $\cancel{\in}$ $U$, we must have $\dim U < \dim \mathcal{P}_4(\mathbb{F}) = 5$, and as the linearly independent (linear independence follows from applying the procedure in example 2.41) list of length 4: $1,(z-2)(z-5),z(z-2)(z-5),z^2(z-2)(z-5)$ consists of vectors that are all in $U$, it must be a basis for $U$ by theorem 2.39.

> (b) We can extend $U$ to a basis for $\mathcal{P}_4(\mathbb{F})$ by appending $z$ to any basis of $U$, as $z \thinspace \cancel{\in} \thinspace U$ and $\dim U = 4$, by [P2A11](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-11/) and theorem 2.39.

> (c) Let $W = \textrm{span}(z)$, then problem (b) implies $\mathcal{P}_4(\mathbb{F}) = U \oplus W$.


