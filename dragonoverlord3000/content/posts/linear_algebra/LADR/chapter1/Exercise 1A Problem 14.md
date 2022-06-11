---
title: "Exercise 1A Problem 14"
date: 2022-06-09T19:13:13+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 14 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $1x = x$ for all $x \in \mathbb{F}^n$

## Solution
Multiplication by scalar is done coordinatewise, and
since $1a = a$ for all $a \in \mathbb{F}$ we must have that:
$$1x \stackrel{D1.10}{=} 1(x_1, x_2, \dots, x_n) \stackrel{D1.17}{=} (1x_1, 1x_2, \dots, 1x_n) = (x_1, x_2, \dots, x_n) \stackrel{D1.10}{=} x$$
Proving that $1$ is a multiplicative identity for $\mathbb{F}^n$.

