---
title: "Exercise 2C Problem 10"
date: 2022-06-27T17:08:39+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 10 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $p_0, p_1, \dots, p_m \in \mathcal{P}(\mathbb{F})$ are such that each $p_j$ has degree $j$. Prove that $p_0, p_1, \dots, p_m$ is a basis of $\mathcal{P}_m(\mathbb{F})$

## Solution
Proceed by induction on $m$. 

> BC: Let $m = 0$, then $p_0 = a_0z^0 = a_0$ is a basis for $\textrm{span}(a_0) = \textrm{span}(1) = \mathcal{P}_0(\mathbb{F})$.

> IH: Suppose that for some $m = k \in \mathbb{N}$ we have  $p_0, p_1, \dots, p_k$ is a basis for $\mathcal{P}_k(\mathbb{F})$ if $p_0, p_1, \dots, p_k \in \mathcal{P}(\mathbb{F})$ are such that each $p_j$ has degree $j$.

> IS: If $p_0, p_1, \dots, p_k, p_{k+1} \in \mathcal{P}(\mathbb{F})$ are such that each $p_j$ has degree $j$. Then $p_{k+1}$ cannot be written in terms of the polynomials $p_0, p_1, \dots, p_k$, as the $z^{k+1}$ cannot be written as a linear combination of lower degree terms. Therefore by [P2A11](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-11/) and the IH, the list $p_0, p_1, \dots, p_k, p_{k+1}$ is therefore a basis for $\mathcal{P}_{k+1}(\mathbb{F})$. Therefore by PMI, it must hold for all $k \in \mathbb{N}_0$.






