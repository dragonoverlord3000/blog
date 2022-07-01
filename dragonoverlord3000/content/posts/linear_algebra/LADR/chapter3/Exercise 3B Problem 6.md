---
title: "Exercise 3B Problem 6"
date: 2022-06-30T21:19:30+02:00
description: "Linear Algebra Done Right - Exercise 3B Problem 6 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove that there does not exist a linear map $T: \mathbb{R}^5 \to \mathbb{R}^5$ such that
$$\textrm{range} \thinspace T = \textrm{null} \thinspace T$$

## Solution
The condition $\textrm{range} \thinspace T = \textrm{null} \thinspace T$ implies $\dim \textrm{range} \thinspace T = \dim \textrm{null} \thinspace T$, which by the fundamental theorem of linear maps implies:
$$5 = \dim \mathbb{R}^5 \stackrel{T3.22}{=} \dim \textrm{range} \thinspace T + \dim \textrm{null} \thinspace T = 2\dim \textrm{null} \thinspace T$$
Implying $\dim \textrm{range} \thinspace T = \dim \textrm{null} \thinspace T = 5/2$ a contradiction.



