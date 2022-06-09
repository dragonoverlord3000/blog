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
Let $\alpha = a + bi$ and $\beta = c + di$, then:
$$1 + 0i = 1 = \alpha \beta = (a + bi)(c + di) = (ac - bd) + (bc + ad)i$$
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
$a$ and $b$, i.e. by $\alpha$.


