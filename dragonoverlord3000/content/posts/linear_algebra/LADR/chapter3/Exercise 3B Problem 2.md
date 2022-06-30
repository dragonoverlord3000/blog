---
title: "Exercise 3B Problem 2"
date: 2022-06-30T20:11:40+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $V$ is a vector space and $S,T \in \mathcal{L}(V,V)$ are such that 
$$\textrm{range} \thinspace S \subset \textrm{null} \thinspace T$$
Prove that $(ST)^2 = 0$

## Solution
As $Tv \in V$ we must have $S(Tv) \in \textrm{range} \thinspace S \subset \textrm{null} \thinspace T$ implying $T(S(Tv)) = 0$ for all $v \in V$. Therefore $(ST)^2v = STSTv = S(T(S(Tv))) = S(0) \stackrel{T3.11}{=} 0$ for all $v \in V$, implying $STST = 0$.






