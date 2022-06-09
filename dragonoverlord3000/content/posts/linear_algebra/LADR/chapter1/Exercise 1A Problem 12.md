---
title: "Exercise 1A Problem 12"
date: 2022-06-09T15:54:44+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $(x + y) + z = x + (y + z)$ for all $x,y,z \in \mathcal{F}$

## Solution
Since addition in $\mathbb{F}^n$ is defined pointwise, the result follows from the result shown in [Problem 5](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1a-problem-5/) as such:
$$(x + y) + z = (x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) + (z_1, z_2, \dots, z_n)$$
$$= ((x_1 + y_1) + z_1, (x_2 + y_2) + z_2, \dots, (x_n + y_n) + z_n)$$
$$= (x_1 + (y_1 + z_1), x_2 + (y_2 + z_2), \dots, x_n + (y_n + z_n))$$
$$= (x_1, x_2, \dots, x_n) + (y_1 + z_1, y_2 + z_2, \dots, y_n + z_n) = x + (y + z)$$
Thus addition is associative in $\mathbb{F}^n$.


