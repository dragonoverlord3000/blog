---
title: "Exercise 1C Problem 12"
date: 2022-06-20T20:50:25+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 12 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove that the union of two subspaces of $V$ is a subspace of $V$ if and only if one of the subspaces is contained in the other.

## Solution
Assume that two subspaces $U_1$ and $U_2$ of $V$ are have non-overlapping elements i.e. that there exists $v \in U_1$ with $v$ $\cancel{\in}$ $U_2$ and $u \in U_2$ with $u$ $\cancel{\in}$ $U_1$. 

Then $v,u \in U_1 \cup U_2$, but if $v + u \in U_1$, then $u = (v + u) - v \in U_1$ a contradiction and similarly if $v + u \in U_2$, then $v = (v + u) - u \in U_2$ a contradiction. Thus $v + u \cancel{\in} U_1 \cup U_2$ and therefore $U_1 \cup U_2$ is not a subspace if none of the two subspaces are contained in the other.

If $U_1$ is contained in $U_2$, then $U_1 \cup U_2 = U_2$ which is a subspace of $V$.
















