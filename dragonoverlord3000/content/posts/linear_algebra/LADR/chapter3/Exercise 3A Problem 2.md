---
title: "Exercise 3A Problem 2"
date: 2022-06-28T13:11:12+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $b,c \in \mathbb{R}$. Define $T: \mathcal{P}(\mathbb{R}) \to \mathbb{R}$ by
$$Tp = \left(3p(4) + 5p^\prime(6) + bp(1)p(2), \int_{-1}^{2}x^3p(x)dx + c\sin p(0)\right)$$
Show that $T$ is linear if and only if $b = c = 0$

## Solution
$(\rightarrow)$ Assume $T$ is a linear map, then if $p = \pi$ we must have:
$$\left(3\pi + b\pi^2, \frac{15}{4}\pi\right) = T\pi = T\left(\frac{\pi}{2} + \frac{\pi}{2}\right) = T\frac{\pi}{2} + T\frac{\pi}{2}$$
$$= 2 \cdot \left(\frac{3}{2}\pi + b\frac{\pi^2}{4}, \frac{15}{8}\pi + c\right) = \left(3\pi + b\frac{\pi^2}{2}, \frac{15}{4}\pi + 2c\right)$$
The second coordinate implies $c = \frac{1}{2}(\frac{15}{4}\pi - \frac{15}{4}\pi) = 0$ and the first coordinate implies $b\frac{\pi^2}{2} = 0$ implying $b = 0$.

$(\leftarrow)$ $b = c = 0$ implies that for all $\lambda, \mu \in \mathbb{F}$ and all $p,q \in \mathcal{P}$:
$$T(\lambda p + \mu q) = \left(3(\lambda p + \mu q)(4) + 5(\lambda p + \mu q)^\prime(6), \int_{-1}^{2}x^3(\lambda p + \mu q)(x)dx\right)$$
$$\stackrel{\spadesuit}{=} \lambda\left(3p(4) + 5p^\prime(6), \int_{-1}^{2}x^3p(x)dx\right) + \mu \left(3q(4) + 5q^\prime(6), \int_{-1}^{2}x^3q(x)dx\right)$$
$$= \lambda Tp + \mu Tq$$
Where spadesuit is due to the linearity of the integral operator and the differential operator as per Example 3.4.
By definition $3.2$ $T$ must therefore be a linear operator - linearity is implied by setting $\lambda = \mu = 1$ proves linearity and setting $\mu = 0$ proves homogeneity.












