---
title: "Exercise 1A Problem 15"
date: 2022-06-09T19:18:36+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 15 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $\lambda (x + y) = \lambda x + \lambda y$ for all $\lambda \in \mathbb{F}$ and all $x, y \in \mathbb{F}^n$

## Solution
Multiplication of an element in $\mathbb{F}^n$ by a scalar is defined coordinate-wise and by [problem 9](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1a-problem-9/) we know that multiplication in $\mathbb{F}$ is distributive, therefore:
$$\lambda (x + y) \stackrel{D1.10 \land D1.12}{=} \lambda (x_1 + y_1, x_2 + y_2, \dots, x_n + y_n)$$
$$\stackrel{D1.17}{=} (\lambda (x_1 + y_1), \lambda (x_2 + y_2), \dots, \lambda (x_n + y_n))$$
$$\stackrel{P1A9}{=} (\lambda x_1 + \lambda y_1, \lambda x_2 + \lambda y_2, \dots, \lambda x_n + \lambda y_n)$$
$$\stackrel{D1.12}{=} (\lambda x_1, \lambda x_2, \dots, \lambda x_n) + (\lambda y_1, \lambda y_2, \dots, \lambda y_n) \stackrel{D1.10 \land D1.12}{=} \lambda x + \lambda y$$
Proving the distributive property of multiplying elements in $\mathbb{F}^n$ by scalars.






