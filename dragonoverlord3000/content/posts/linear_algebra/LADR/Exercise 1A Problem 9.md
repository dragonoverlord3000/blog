---
title: "Exercise 1A Problem 9"
date: 2022-06-09T06:49:24+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 9 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $\lambda (\alpha + \beta) = \lambda \alpha + \lambda \beta$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

## Solution
Let $\alpha = a + bi$, $\beta = c + di$ and $\lambda = e + fi$, then:
$$\lambda (\alpha + \beta) = (e + fi)\left((a + bi) + (c + di)\right) = (e + fi)\left((a + c) + (b + d)i\right)$$
$$= (ea + ec - fb - fd) + (eb + ed + af + cf)i$$
$$= \left((ea - fb) + (ec - fd)\right) + \left((eb + af) + (ed + cf)\right)i$$
$$= \left((ea - fb) + (eb + af)i\right) + \left((ec - fd) + (ed + cf)i\right)$$
$$= (e + fi)(a + bi) + (e + fi)(c + di) = \lambda \alpha + \lambda \beta$$
Proving the distributive property of complex numbers.

