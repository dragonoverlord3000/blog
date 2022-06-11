---
title: "Exercise 1A Problem 13"
date: 2022-06-09T19:03:10+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 13 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $(ab)x = a(bx)$ for all $x \in \mathbb{F}^n$ and $a,b \in \mathbb{F}$

## Solution
Since multiplication of an element in $\mathbb{F}^n$ by a scalar is defined coordinate-wise, the result follows from the result shown in [Problem 6](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1a-problem-6/) as such:
$$(ab)x \stackrel{D1.10}{=} (ab) (x_1, x_2, \dots, x_n) \stackrel{D1.17}{=} ((ab)x_1, (ab)x_2, \dots, (ab)x_n)$$
$$\stackrel{P1A6}{=} (a(bx_1), a(bx_2), \dots, a(bx_n)) \stackrel{D1.17}{=} a(bx_1, bx_2, \dots, bx_n) \stackrel{D1.10 \land D1.17}{=} a(bx)$$
Proving the associativity of multiplication of an element in $\mathbb{F}^n$ by a scalar.


