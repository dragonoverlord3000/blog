---
title: "Exercise 1A Problem 4"
date: 2022-06-08T15:04:55+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $\alpha + \beta = \beta + \alpha$ for all $\alpha, \beta \in \mathbb{C}$.


## Solution
Let $\alpha = a + bi$ and $\beta = c + di$ for real numbers $a,b,c$ and $d$. Then by commutativity of real numbers we must have:
$$\alpha + \beta = (a + bi) + (c + di) \stackrel{D1.1}{=} (a + c) + (b + d)i$$
$$= (c + a) + (d + b)i \stackrel{D1.1}{=} (c + di) + (a + bi) = \beta + \alpha$$
Implying that complex numbers commute under addition.




