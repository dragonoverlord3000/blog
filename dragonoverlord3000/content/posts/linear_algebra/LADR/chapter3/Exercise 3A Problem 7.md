---
title: "Exercise 3A Problem 7"
date: 2022-06-28T17:36:14+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that every linear map from a 1-dimensional vector space to itself is multiplication by some scalar. More precisely, prove that if $\dim V = 1$ and $T \in \mathcal{L}(V,V)$, then there exists $\lambda \in \mathbb{F}$ such that $Tv = \lambda v$ for all $v \in V$

## Solution
Let $u \in V$ be non-zero, then the list $u$ is a basis for $V$ as per Example 2.18 and theorem 2.39. Therefore any $v \in V$ is in $\textrm{span}(u)$ because a basis is a spanning list by definition 2.27 or equivalentely, for all $v \in V$ there exist an $\alpha \in \mathbb{F}$ such that $v = \alpha u$.

As $Tu \in V$ we must therefore have $Tu = \lambda u$ for some 
$\lambda \in \mathbb{F}$ and therefore 
$$Tv = T(\alpha u) \stackrel{D3.2}{=} \alpha (Tu) = \alpha (\lambda u) \stackrel{D1.19}{=} (\alpha \lambda) u$$
$$\stackrel{E1.4}{=} (\lambda \alpha) u \stackrel{D1.19}{=} \lambda (\alpha u) = \lambda v$$
for all $v \in V$.






