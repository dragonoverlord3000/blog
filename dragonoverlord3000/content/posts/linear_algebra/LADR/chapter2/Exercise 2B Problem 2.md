---
title: "Exercise 2B Problem 2"
date: 2022-06-26T11:54:27+02:00
description: "Linear Algebra Done Right - Exercise 2B Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Verify all the assertions in Example 2.28

## Solution
1. Any vector $(x_1, x_2, \dots, x_n) \in \mathbb{F}^n$ can be written as a linear combination of the given list as such $(x_1, x_2, \dots, x_n) = x_1(1,0,\dots,0) + x_2(0,1,0,\dots,0) + \dots + x_n(0,\dots,0,1)$, therefore the list spans $\mathbb{F}^n$. The list is also clearly linearly independent and therefore a basis.

2. The list $(1,2), (3,5)$ is a basis of $\mathbb{F}^2$ because any vector $(x,y)$ can be written as a linear combination of $(1,2), (3,5)$ as such $(x,y) = (3y - 5x)(1,2) + (2x - y)(3,5)$, also $(1,0),(0,1)$ is a basis of $\mathbb{F}^2$ by (1), therefore by theorem 2.23 the list $(1,2), (3,5)$ must be linearly independent.

3. $a_1(1,2,-4) + a_2(7,-5,6) = 0$ implies $a_1 = -7a_2$ by the first coordinate and therefore by the second coordinate $0 = 2a_1 - 5a_2 = -19a_2$ implying $a_2 = 0$ and therefore $a_1 = 0$. Therefore $(1,2,-4), (7,-5,6)$ is a linearly independent list in $\mathbb{F}^3$. The list $(1,0,0), (0,1,0), (0,0,1)$ is the standard basis of $\mathbb{F}^3$ and by theorem 2.23 the list $(1,2,-4), (7,-5,6)$ can therefore not be a spanning list and by extension a basis.

4. By (2) we know that the list $(1,2), (3,5)$ spans $\mathbb{F}^2$ and therefore so will $(1,2), (3,5), (4,13)$, but the list $(1,0),(0,1)$ is a basis for $\mathbb{F}^2$ by (1) and therefore by theorem 2.23, the list $(1,2), (3,5), (4,13)$ will be linearly dependent.

5. Any vector $(x,x,y)$ in the given set can be uniquely written as the linear combination $x(1,1,0) + y(0,0,1)$ and by theorem 2.29, the list $(1,1,0), (0,0,1)$ must therefore be a basis for the given set.

6. The given vector space is $\lbrace (x,y,-x-y) | x,y \in \mathbb{F} \rbrace$ and since any vector $(x,y,-x-y)$ in the vector space can be uniquely written as $x(1,0,-1) + y(0,1,-1)$ and therefore by theorem 2.29, the list $(1,0,-1),(0,1,-1)$ is a basis for the given vector space.

7. Any polynomial $p(z) \in \mathcal{P}_m(\mathbb{F})$ can be written uniquely in terms of the given list as such $a_0 \cdot 1 + a_1z + \dots + a_mz^m$, therefore by theorem 2.29 the list $1,z,z^2,\dots,z^m$ is a basis for $\mathcal{P}_m(\mathbb{F})$.







