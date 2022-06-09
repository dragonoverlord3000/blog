---
title: "Exercise 1A Problem 6"
date: 2022-06-08T21:37:50+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that $(\alpha \beta) \lambda = \alpha (\beta \lambda)$ for all $\alpha, \beta, \lambda \in \mathbb{C}$

## Solution
Let $\alpha = a + bi$, $\beta = c + di$ and $\lambda = e + fi$. Then by the associativity
of real numbers:
$$(\alpha \beta) \lambda = \left((a + bi)(c + di)\right)(e + fi) = \left(ac - df + (bc + ad)i\right)(e + fi)$$
$$= (ace - bdf - bcf - adf) + (acf - bdf + bce + ade)i$$
$$= a(ce - df) - b(de + cf) + ai(cf + de) + bi(ce - df)$$
$$= (a + bi)(ce - df) + (ai - b)(de + cf)$$
$$= (a + bi)(ce - df) + (a + bi)(de + cf)i$$
$$= (a + bi)\left((ce - df) + (de + cf)i\right)$$
$$= (a + bi)\left((c + di)(e + fi)\right) = \alpha (\beta \lambda)$$
Proving the associativity complex numbers under multiplication.


























