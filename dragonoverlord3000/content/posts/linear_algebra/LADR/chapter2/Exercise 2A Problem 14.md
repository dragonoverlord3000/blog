---
title: "Exercise 2A Problem 14"
date: 2022-06-25T22:59:49+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 14 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove that $V$ is infinite-dimensional if and only if there is a sequence $v_1, v_2, \dots$ of vectors in $V$ such that $v_1, \dots, v_m$ is linearly independent for every positive integer $m$

## Solution
$(\rightarrow)$ $V$ being infinite-dimensional implies that we can always find a $v_{m+1}$ that is not in the span of linearly independent vectors $v_1, \dots, v_m$ for all positive integers $m$. By [P2A11](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter2/exercise-2a-problem-8/) we can therefore construct a sequence $v_1, v_2, \dots$ of vectors with the property that for any $m \in \mathbb{N}$ we have linear independence for $v_1, v_2, \dots, v_m$.

$(\leftarrow)$ Given that we have an infinite sequence of linearly independent vectors in $V$ theorem 2.23 implies that no finite list of vectors will span the space, therefore $V$ is infinite dimensional.
















