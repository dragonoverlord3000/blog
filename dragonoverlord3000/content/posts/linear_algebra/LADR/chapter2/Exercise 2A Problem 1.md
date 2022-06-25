---
title: "Exercise 2A Problem 1"
date: 2022-06-25T12:58:21+02:00
description: "Linear Algebra Done Right - Exercise 2A Problem 1 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $v_1, v_2, v_3, v_4$ spans $V$. Prove that the list 
$$v_1 - v_2, v_2 - v_3, v_3 - v_4, v_4$$
also spans $V$

## Solution
Let $u = a_1v_1 + a_2v_2 + a_3v_3 + a_4v_4$ where $a_1,a_2,a_3,a_4 \in \mathbb{F}$ and define $b_i$ as follows: $b_1 = a_1, b_2 - b_1 = a_2, b_3 - b_2 = a_3$ and $b_4 - b_3 = a_4$. Then we must have that:
$$u = a_1v_1 + a_2v_2 + a_3v_3 + a_4v_4$$
$$= b_1v_1 + (b_2 - b_1)v_2 + (b_3 - b_2)v_3 + (b_4 - b_3)v_4$$
$$= b_1(v_1 - v_2) + b_2(v_2 - v_3) + b_3(v_3 - v_4) + b_4v_4$$
Thus $u \in \textrm{span}(v_1,v_2,v_3,v_4) \iff u \in \textrm{span}(v_1 - v_2,v_2 - v_3,v_3 - v_4,v_4)$



















