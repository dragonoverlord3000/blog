---
title: "Exercise 1A Problem 7"
date: 2022-06-09T05:56:32+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 7 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that for every $\alpha \in \mathbb{C}$, there exists a unique $\beta \in \mathbb{C}$
such that $\alpha + \beta = 0$

## Solution
Let $\alpha, \beta, \lambda \in \mathbb{F}$ and let $\alpha + \beta = 0$ and $\alpha + \lambda = 0$, then
$$\beta = \beta + 0 = \beta + (\alpha + \lambda) \stackrel{P1A5}{=} (\beta + \alpha) + \lambda = 0 + \lambda = \lambda$$
Thus any additive inverse of $\alpha$ is unique, existence can be shown by seeing that if $\alpha = a + bi$, then $\beta = -a - bi$ is an additive inverse. *Proof:*
$$\alpha + \beta = (a + bi) + (-a - bi) \stackrel{D1.1}{=} (a - a) + (b - b)i = 0 + 0i = 0$$
Proving existence of an additive inverse.

<!-- Let $\alpha = a + bi$ and $\beta = c + di$, then: 
$$0 + 0i = 0 = \alpha + \beta = (a + bi) + (c + di) \stackrel{D1.1}{=} (a + c) + (b + d)i$$
Comparing real and imaginary parts of the left- and right-hand sides, 
gives us that $0 = a + c$ and $0 = b + d$, thus $c = -a$ and $d = -b$.
Therefore $(a + bi) + (c + di) = 0 \iff c = -a \land d = -b$ giving us a unique
additive inverse $\beta$ for every complex number $\alpha$. -->

