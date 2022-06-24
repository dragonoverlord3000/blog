---
title: "Exercise 1C Problem 19"
date: 2022-06-24T14:52:00+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 19 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove or give counterexample: if $U_1$, $U_2$, $W$ are subspaces of $V$ such that
$$U_1 + W = U_2 + W$$
then $U_1 = U_2$

## Solution
Here's a counterexample: let $W = \lbrace (x,y,0) | x,y \in \mathbb{F} \rbrace$, $U_1 = \lbrace (0,0,z) | z \in \mathbb{F} \rbrace$ and $U_2 = \lbrace (0,z,z) | z \in \mathbb{F} \rbrace$, then by example 1.43:
$$U_1 + W \stackrel{D1.36}{=} \mathbb{F}^3$$
But we also have:
$$U_2 + W \stackrel{D1.36}{=} \mathbb{F}^3$$
Therefore $U_1 + W = U_2 + W$, but clearly $U_1 \neq U_2$.

