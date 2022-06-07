---
title: "Exercise 1A Problem 1"
date: 2022-06-07T16:31:26+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 1 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose <i>a</i> and <i>b</i> are real numbers, not both 0. Find real numbers <i>c</i> and <i>d</i> such that </br>
$$\frac{1}{a + bi} = c + di$$

## Solution
A standard trick when dealing with the reciprocal of a complex numbers is to multiply
the numerator and the denominator by it's complex conjugate, as this will make the 
denominator real. Applying this trick:
\begin{equation}
    c + di = \frac{1}{a + bi} = \frac{a - bi}{a - bi} \cdot \frac{1}{a + bi} = \frac{a}{a^2 + b^2} + \frac{b}{a^2 + b^2}i
\end{equation}
From comparing the real and imaginary parts of the left and right hand sides above:
\begin{align}
&c = \frac{a}{a^2 + b^2} &&\land &&d=\frac{b}{a^2 + b^2}
\end{align}



