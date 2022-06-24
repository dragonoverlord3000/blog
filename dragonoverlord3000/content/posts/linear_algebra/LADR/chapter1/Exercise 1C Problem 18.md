---
title: "Exercise 1C Problem 18"
date: 2022-06-24T14:34:11+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 18 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Does the operation of addition on the subspaces of $V$ have an additive identity? Which subspaces have additive inverses?

## Solution
Yes, addition of subspaces does have an additive identity since $\lbrace 0 \rbrace$ is always a subspace of any vector space $V$ and has the property that if $U$ is a subspace of $V$, then $U + \lbrace 0 \rbrace \stackrel{D1.36}{=} \lbrace u + v | u \in U, v \in \lbrace 0 \rbrace \rbrace = \lbrace u | u \in U \rbrace = U$. Actually any subset of $U$ is an additive identity of $U$ and $\lbrace 0 \rbrace$ is a subspace of all vector spaces.

The only subspace that has an additive inverse is $\lbrace 0 \rbrace$ since $U \subseteq U + W$ for all subspaces $U,W$ of $V$, by definition $1.36$. Therefore $U \subseteq U + W = \lbrace 0 \rbrace$ implies $U = \lbrace 0 \rbrace$ and likewise for $W$.


