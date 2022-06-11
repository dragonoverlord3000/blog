---
title: "Exercise 1A Problem 11"
date: 2022-06-09T15:39:27+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 11 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Explain why there does not exist $\lambda \in \mathbb{C}$ such that
$$\lambda (2 - 3i, 5 + 4i, -6 + 7i) = (12 - 5i, 7 + 22i, -32 - 9i)$$

## Solution
From the first coordinate and D1.17 we have:
$$\lambda = \frac{2 - 3i}{12 - 5i} = \frac{12 + 5i}{12 + 5i}\frac{2 - 3i}{12 - 5i} = \frac{(24 + 15) + (10 - 36)i}{12^2 + 5^2} = \frac{3}{13} - \frac{2}{13}i$$
But from the second coordinate and D1.17 we have:
$$\lambda = \frac{7 + 22i}{5 + 4i} = \frac{5 - 4i}{5 - 4i}\frac{7 + 22i}{5 + 4i} = \frac{(35 + 88) + (-28 + 110)i}{5^2 + 4^2} = 3 + 2i$$
Since $3/13 - 2/13i \neq 3 + 2i$ we have a contradiction i.e. there can not exist such a lambda in $\mathbb{C}$.




