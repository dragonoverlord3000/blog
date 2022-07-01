---
title: "Exercise 3B Problem 4"
date: 2022-06-30T20:49:58+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 4 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that
$$\lbrace T \in \mathcal{L}(\mathbb{R}^5, \mathbb{R}^4) | \dim \textrm{null} \thinspace T > 2 \rbrace$$
is not a subspace of $\mathcal{L}(\mathbb{R}^5, \mathbb{R}^4)$

## Solution
Let $U = \lbrace T \in \mathcal{L}(\mathbb{R}^5, \mathbb{R}^4) | \dim \textrm{null} \thinspace T > 2 \rbrace$, then $T_1 \in U$ defined by $T_1(x_1, x_2, x_3, x_4, x_5) = (x_1,x_2,0,0)$ and $T_2 \in U$ defined by $T_2(x_1, x_2, x_3, x_4, x_5) = (0,0,x_3,x_4)$, where $x_1, \dots, x_5 \in \mathbb{R}$. But their sum:
$$(T_1 + T_2)(x_1, x_2, x_3, x_4, x_5) \stackrel{D3.6}{=} T_1(x_1, x_2, x_3, x_4, x_5) + T_2(x_1, x_2, x_3, x_4, x_5)$$ 
$$= (x_1, x_2,0,0) + (0,0,x_3,x_4) \stackrel{D1.12}{=} (x_1,x_2,x_3,x_4)$$
Therefore $\dim \textrm{range} \thinspace T = \dim \mathbb{R}^4 = 4$ which by the fundamental theorem of linear maps implies $\dim \textrm{null} \thinspace (T_1 + T_2) = 5 - 4 = 1$, therefore $U$ is not closed under addition.





