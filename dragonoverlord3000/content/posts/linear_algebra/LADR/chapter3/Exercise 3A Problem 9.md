---
title: "Exercise 3A Problem 9"
date: 2022-06-28T20:18:28+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 9 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Give an example of a function $\phi : \mathbb{C} \to \mathbb{C}$ such that
$$\phi(w + z) = \phi(w) + \phi(z)$$
for all $w,z \in \mathbb{C}$ but $\phi$ is not linear. (Here $\mathbb{C}$ is thought of as a complex vector space)

## Solution
Let $\phi(z) = \textrm{Re}(z)$ for all $z \in \mathbb{C}$, let now $a,b,c,d \in \mathbb{R}$ such that $z = a + bi$ and $w = c + di$. Then we must have:
$$\phi(z + w) = \phi((a + bi) + (c + di)) \stackrel{D1.1}{=} \phi((a + c) + (b + d)i)$$
$$= a + c = \phi(a + bi) + \phi(c + di) = \phi(z) + \phi(w)$$
But consider the function applied to $1 + i$ under scalar multiplication by $i$:
$$i = i \cdot 1 = i \cdot \phi(1 + i) = \phi(i(1 + i)) = \phi(-1 + i) = -1$$
A contradiction.





