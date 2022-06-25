---
title: "Exercise 2A Problem 2"
date: 2022-06-25T13:57:18+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Verify the assertions in Example 2.18

## Solution
1. $av = 0 \stackrel{P1B2}{\iff} a = 0 \lor v = 0$ , thus $a = 0$ if $v \neq 0$ and if $v = 0$, then $v$ is linear dependent by definition 2.17

2. Suppose the list $v,u \in V$ is linearly dependent, then there exist non-zero $a_1, a_2 \in \mathbb{F}$ such that $a_1u + a_2v = 0$, thus $u = -\frac{a_2}{a_1}v$. That is, the list $u,v$ is linearly dependent if and only if $u$ is a scalar multiple of $v$ (and the other way around). Therefore, the contrapositive is also true, i.e. $u,v$ is linearly independent if and only if neither vector is a scalar multiple of the other.

3. Let $x,y,z \in \mathbb{F}$, then 
$$(0,0,0,0) = 0 = x(1,0,0,0) + y(0,1,0,0) + z(0,0,1,0)$$
$$\stackrel{D1.17 \land D1.12}{=} (x,y,z,0)$$
That is $x=y=z=0$. Therefore the list $(1,0,0,0), (0,1,0,0), (0,0,1,0)$ is linearly independent by definition 2.19.

4. Let $a_0, a_1, \dots, a_m \in \mathbb{F}$, then
$$0 \cdot 1 + 0z + \dots + 0z^m = 0 = a_0 + a_1 z + a_2 z^2 + \dots + a_mz^m$$
implies $a_0 = a_1 = \dots + a_m$ by equating coefficients.









