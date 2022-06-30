---
title: "Exercise 3A Problem 8"
date: 2022-06-28T20:01:22+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 8 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Give an example of a function $\phi : \mathbb{R}^2 \to \mathbb{R}$ such that
$$\phi(av) = a\phi(v)$$
for all $a \in \mathbb{R}$ and all $v \in \mathbb{R}^2$ but $\phi$ is not linear.

## Solution
Let $\phi((x,y)) = \textrm{sgn}(x)\sqrt{x^2 + y^2}$, then:
$$\phi(a(x,y)) = \phi((ax,ay)) = \textrm{sgn}(ax)|a|\sqrt{x^2 + y^2}$$ 
$$= a \cdot \textrm{sgn}(x)\sqrt{x^2 + y^2} = a \phi((x,y))$$
But consider $(0,1)$ and $(1,0)$, then:
$$\sqrt{2} = \phi((1,1)) = \phi((1,0) + (0,1)) = \phi((1,0)) + \phi((0,1)) = 1 + 1 = 2$$
A contradiction.













