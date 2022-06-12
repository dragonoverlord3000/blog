---
title: "Exercise 1B Problem 3"
date: 2022-06-12T17:50:09+02:00
description: "Linear Algebra Done Right - Exercise 1B Problem 3 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v, w \in V$. Explain why there exists a unique $x \in V$ such that $v + 3x = w$

## Solution
Suppose that $x,x^\prime \in V$ satisfies $v + 3x = w = v + 3x^\prime$, then adding the 
additive inverse of $v$ to both sides will reduce the equality to $3x = 3x^\prime$, dividing by $3$ on both sides results in $x = x^\prime$, thus $x$ is *unique*. 


Now, let $x = \frac{1}{3}(w - v)$, then:
$$v + 3x = v + 3\left(\frac{1}{3}(w - v)\right) \stackrel{P1A13}{=} v + \left(3 \cdot \frac{1}{3}\right)(w - v) = v + 1(w - v) \stackrel{D1.19}{=} w$$
Proving *existence* of such an $x$.

