---
title: "Exercise 1A Problem 8"
date: 2022-06-09T06:05:54+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that for every $\alpha \in \mathbb{C}$ with $\alpha \neq 0$, there exists a unique $\beta \in \mathbb{C}$ such that $\alpha \beta = 1$

## Solution
Let $\alpha,\beta,\lambda \in \mathbb{C}$ with $\alpha\beta = \alpha\lambda = 1$, then:
$$\beta = \beta \cdot 1 = \beta(\alpha\lambda) \stackrel{P1A6}{=} (\beta\alpha)\lambda \stackrel{E1.4}{=} (\alpha\beta)\lambda = 1 \cdot \lambda = \lambda$$
Proving uniqueness of the multiplicative inverse $\beta$, existence was shown in [P1A1](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1a-problem-1/).

<!-- Let $\alpha = a + bi$ and $\beta = c + di$, then:
$$1 + 0i = 1 = \alpha \beta = (a + bi)(c + di) \stackrel{D1.1}{=} (ac - bd) + (bc + ad)i$$
Comparing the real- and imaginary parts of the left and right hand sides
above gives us the following system of equations:
$$ac - bd = 1 \land bc + ad = 0$$
Multiplying the equation on the left by $a$ gives us:
$$a = a^2c - abd = a^2c - b(ad) = a^2c - b(-bc) = c(a^2 + b^2)$$
Similarly, multiplying by $b$:
$$b = bac - b^2d = a(bc) - b^2d = a(-ad) - b^2d = -d(a^2 + b^2)$$
But this implies that:
$$c = \frac{a}{a^2 + b^2} \land d = -\frac{b}{a^2 + b^2}$$
Thus $c$ and $d$, and therefore $\beta$, exists and are uniquely determined by
$a$ and $b$, i.e. by $\alpha$. -->


