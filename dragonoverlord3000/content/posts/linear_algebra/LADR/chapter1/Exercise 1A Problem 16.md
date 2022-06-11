---
title: "Exercise 1A Problem 16"
date: 2022-06-09T19:31:10+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 16 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $(a + b)x = ax + bx$ for all $a,b \in \mathbb{F}$ and all $x \in \mathbb{F}^n$

## Solution
Multiplication of elements in $\mathbb{F}^n$ by scalars is defined coordinate-wise and from [problem 9](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1a-problem-9/) we know that multiplication of elements in $\mathbb{F}$ is distributive. Therefore:
$$(a + b)x \stackrel{D1.10}{=} (a + b)(x_1, x_2, \dots, x_n) $$
$$\stackrel{D1.17}{=} ((a + b)x_1, (a+b)x_2, \dots, (a+b)x_n)$$
$$\stackrel{E1.4 \land P1A9}{=} (ax_1 + bx_1, ax_2 + bx_2, \dots, ax_n + bx_n)$$
$$ \stackrel{D1.12 \land D1.17}{=} a (x_1, x_2, \dots, x_n) + b (x_1, x_2, \dots, x_n)  \stackrel{D1.10}{=} ax + bx$$
Proving that elements of $\mathbb{F}^n$ distribute onto sums of scalars. 

