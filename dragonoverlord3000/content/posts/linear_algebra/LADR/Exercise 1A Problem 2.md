---
title: "Exercise 1A Problem 2"
date: 2022-06-08T05:43:05+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 2 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Show that
\begin{equation}
\frac{-1 + \sqrt{3}i}{2}
\end{equation}
is a cube root of 1 (meaning that it's cube equals 1).

## Solution
One solution is to take the cube of the given complex number and observe that
it equals one. 
\begin{equation}
\left(\frac{-1 + \sqrt{3}i}{2}\right)^3 = \frac{1}{8}\left(-1 + \sqrt{3}i\right)^3 
\end{equation}
$$= \frac{1}{8}\left(-1 + 3\sqrt{3}i - 3(-3) -3\sqrt{3}i\right) = \frac{1}{8} \cdot 8 = 1$$
Another is to notice that cos(2&#960/3) = -1/2 and that sin(2&#960/3) = i&#8730 3 / 2,
which by eulers formula implies:
\begin{equation}
   \sqrt[3]{1} = \sqrt[3]{e^{2\pi i}} = e^{\frac{2\pi}{3}i} = \cos\left(\frac{2\pi}{3}\right) + i\sin\left(\frac{2\pi}{3}\right) = \frac{-1 + \sqrt{3}i}{2}
\end{equation}



