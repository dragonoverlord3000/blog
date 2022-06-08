---
title: "Exercise 1A Problem 3"
date: 2022-06-08T15:03:55+02:00
description: "Linear Algebra Done Right - Exercise 1A Problem 1 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Find two distinct square roots of *i*.

## Solution 
First write *i* in complex exponential form, then take it's square root and then use euler's formula, as such:
\begin{equation}
    \sqrt{i} = \sqrt{e^{\frac{\pi}{2} i}} = \pm e^{\frac{\pi}{4}i} = \pm \cos\left(\frac{\pi}{4}\right) \pm i\sin\left(\frac{\pi}{4}\right) = \pm \frac{\sqrt{2}}{2}(1 + i) 
\end{equation}
Another approach is to let the square root of *i* equal *a + bi* and then solve for *a* and *b* as follows:
\begin{align}
    &\sqrt{i} = a + bi &&\to &&&i = (a + bi)^2 = a^2 - b^2 + 2abi
\end{align}
From which it must follow that:
\begin{equation}
    a^2 - b^2 = 0
\end{equation}
\begin{equation}
    2ab = 1
\end{equation}
Therefore |*a*| = |*b*| and *ab = 1/2*. Implying that:
\begin{align}
    &a^2 = b^2 = \frac{1}{2} &&\to &&&a = b = \pm \frac{\sqrt{2}}{2}
\end{align}
And we're done.






