---
title: "Exercise 3B Problem 10"
date: 2022-07-01T18:58:20+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 10 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, \dots, v_n$ spans $V$ and $T \in \mathcal{L}(V,W)$. Prove that the list $Tv_1, \dots, Tv_n$ spans range $T$

## Solution
As $v_1, \dots, v_n$ spans $V$, any $v \in V$ can be written as a linear combination of $v_1, \dots, v_n$ as per definition 2.5. Therefore, for any $v \in V$ there exist $a_1, \dots, a_n \in \mathbb{F}$ such that $v = a_1v_1 + \dots + a_nv_n$ implying that:
$$Tv = T(a_1v_1 + \dots + a_nv_n) \stackrel{D3.2}{=} a_1(Tv_1) + \dots + a_n(Tv_n) \in \textrm{range} \thinspace T$$
Proving that $\textrm{span} (Tv_1, \dots, Tv_n) \subseteq \textrm{range} \thinspace T$. If on the other hand $Tv \in \textrm{range} \thinspace T$, then there exist $b_1, \dots, b_m \in \mathbb{F}$ such that for any $Tv \in W$:
$$Tv = b_1(Tu_1) + \dots + b_m(Tu_m) \stackrel{D3.2}{=} T(b_1u_1 + \dots + b_mu_m)$$
for $u_1, \dots, u_m \in V$. And $v_1, \dots, v_n$ being a spanning list for $V$ implies the existence of scalars $c_1 \dots c_n \in \mathbb{F}$ such that $b_1u_1 + \dots + b_mu_m = c_1v_1 + \dots + c_nv_n$ and therefore $\textrm{span} (Tv_1, \dots, Tv_n) \subseteq \textrm{range} \thinspace T$.

Thus $\textrm{span} (Tv_1, \dots, Tv_n) = \textrm{range} \thinspace T$.



