---
title: "Exercise 3B Problem 1"
date: 2022-06-30T19:58:26+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 1 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Give an example of a linear map $T$ such that $\dim \textrm{null} \thinspace\thinspace T = 3$ and $\dim \textrm{range} \thinspace\thinspace T = 2$


## Solution
Let $T: \mathbb{R}^5 \to \mathbb{R}^2$ defined by $T(x_1, x_2, x_3, x_4, x_5) = (x_1,x_2)$ for all $x_1, x_2, x_3, x_4, x_5 \in \mathbb{R}$. Then $\textrm{null} \thinspace T = \lbrace (0,0,x_1,x_2,x_3) | x_1,x_2,x_3 \in \mathbb{R} \rbrace$ and also $\textrm{range} \thinspace T = \lbrace (x_1,x_2) | x_1,x_2 \in \mathbb{R} \rbrace = \mathbb{R}^2$. 

Therefore $\dim \textrm{null} \thinspace T = 3$ and $\dim \textrm{range} \thinspace T = 2$.


