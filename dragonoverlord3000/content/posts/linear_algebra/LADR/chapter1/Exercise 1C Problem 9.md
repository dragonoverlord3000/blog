---
title: "Exercise 1C Problem 9"
date: 2022-06-16T05:14:01+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 9 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
A function $f: \mathbb{R} \to \mathbb{R}$ is called <i><b>periodic</b></i> if there exists a positive number $p$ such that $f(x) = f(x + p)$ for all $x \in \mathbb{R}$. Is the set of periodic functions from $\mathbb{R} \to \mathbb{R}$ a subspace of $\mathbb{R}^\mathbb{R}$? Explain.

## Solution
No, the sum of two periodic functions is not necesarrily periodic. *Proof*: 
Take for example $f(x) = f(x+1)$ and $g(x) = g(x + \pi)$, which have periods of $1$ and $\pi$ respectively. Then for their sum $h(x) = f(x) + g(x)$ to be periodic, there has to be some $p \in \mathbb{R}^+$ such that $h(x) = h(x + p)$ for all $x$. Such a $p$ must satisfy that $g(x) = g(x + p)$ and $f(x) = f(x + p)$ the first of which only happens when $p \in \mathbb{N}$ and the second of which only happens when $p = m\pi$ for $m \in \mathbb{N}$, but $m\pi = p = n$ implies $\pi = \frac{n}{m}$ for $m,n \in mathbb{N}$ - this is a contradiction as $\pi$ is irrational.

As the subset of periodic functions over $\mathbb{R}$ is not closed under addition it's not a subspace.









