---
title: "Exercise 3A Problem 6"
date: 2022-06-28T16:59:13+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove the assertions in 3.9.

## Solution
1. Associativity

Multiplication of linear maps is defined as function composition, therefore:
$$((T_1 T_2) T_3)(v) = (T_1T_2)(T_3 v) = T_1(T_2(T_3v))$$
$$= T_1((T_2T_3)(v)) = (T_1(T_2T_3))(v)$$

Implying that $(T_1T_2)T_3 = T_1(T_2T_3)$.

2. Identity

Let $T \in \mathcal{L}(V,W)$ and $I$ be the identitymap on $V$ and $W$ respectively:

$$(TI)(v) = T(Iv) = Tv$$
$$(IT)(v) = I(Tv) = Tv$$

3. Distributive properties

Let $T, T_1, T_2 \in \mathcal{L}(U,V)$ and $S, S_1, S_2 \in \mathcal{L}(V,W)$, then:

$$((S_1 + S_2)T)(v) = (S_1 + S_2)(Tv)$$ 
$$\stackrel{D3.6}{=} S_1(Tv) + S_2(Tv) \stackrel{D3.6}{=} (S_1T + S_2T)(v)$$

And also:
$$(S(T_1 + T_2))(v) = S((T_1 + T_2)(v)) \stackrel{D3.6}{=} S(T_1 v + T_2 v)$$ 
$$\stackrel{D3.2}{=} S(T_1v) + S(T_2v) = (ST_1)(v) + (ST_2)(v)$$



