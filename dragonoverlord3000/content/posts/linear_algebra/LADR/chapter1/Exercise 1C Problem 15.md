---
title: "Exercise 1C Problem 15"
date: 2022-06-23T17:30:55+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 15 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U$ is a subspace of $V$. What is $U + U$?

## Solution
By directly applying the definition of sums of subspaces:
$$U + U \stackrel{D1.36}{=} \lbrace 2u | u \in U \rbrace$$
Now let $v = 2u$, then $v \in U$, because $U$ is a subspace and thus closed under multiplication. Therefore:
$$U + U = \lbrace v | v \in U \rbrace = U$$







