---
title: "Exercise 2B Problem 7"
date: 2022-06-26T15:49:11+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove or give counterexample: If $v_1, v_2, v_3, v_4$ is a basis of $V$ and $U$ is a subspace of $V$ such that $v_1,v_2 \in U$ and $v_3$ $\cancel{\in}$ $U$ and $v_4$ $\cancel{\in}$ $U$, then $v_1,v_2$ is a basis of $U$.

## Solution
The list $v_1, v_2$ is linearly independent because the list $v_1, v_2, v_3, v_4$ is a basis. Suppose now that $v_1, v_2$ does not span $U$, then there exists $u \in U$ such that $u$ $\cancel{\in}$ $\textrm{span}(v_1,v_2)$. Therefore by [P2A11](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-11/), the list $v_1, v_2, u$, is linearly independent. 

Now since $v_3$ $\cancel{\in}$ $U$ and $v_4$ $\cancel{\in}$ $U$ we can extend the list $v_1, v_2, u$ to the linearly independent list $v_1, v_2, u, v_3, v_4$ which spans $V$ because $v_1, v_2, v_3, v_4$ is a basis of $V$. But this contradicts theorem 2.23 and thus $v_1,v_2$ must span $U$ implying that it is a basis for $U$.






