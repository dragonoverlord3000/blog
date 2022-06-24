---
title: "Exercise 1C Problem 20"
date: 2022-06-24T15:03:35+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 20 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem 
Suppose
$$U = \lbrace (x,x,y,y) \in \mathbb{F}^4 |x,y \in \mathbb{F} \rbrace$$
Find a subspace $W$ of $\mathbb{F}^4$ such that $\mathbb{F}^4 = U \oplus W$

## Solution
Let $W = \lbrace (0,x^\prime,0,y^\prime) \in \mathbb{F}^4 | x^\prime,y^\prime \in \mathbb{F} \rbrace$, then:
$$U + W \stackrel{D1.36}{=} \lbrace (x,x,y,y) + (0,x^\prime,0,y^\prime) | x,y,x^\prime,y^\prime \in \mathbb{F} \rbrace$$
$$\stackrel{D1.12}{=} \lbrace (x,x + x^\prime,y,y + y^\prime) | x,y,x^\prime,y^\prime \in \mathbb{F} \rbrace$$
Define $x_1 = x, x_2 = x + x^\prime, x_3 = y$ and $x_4 = x + y^\prime$, then:
$$U + W = \lbrace (x_1, x_2, x_3, x_4) | x_1, x_2, x_3, x_4 \in \mathbb{F} \rbrace = \mathbb{F}^4$$
Also it's clear that $U \cap W = \lbrace 0 \rbrace$, thus $U \oplus W = \mathbb{F}^4$.

