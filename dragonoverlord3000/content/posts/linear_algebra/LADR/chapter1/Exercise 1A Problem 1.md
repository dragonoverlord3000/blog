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
<!-- ### Algebra -->
A standard trick when dealing with the reciprocal of a complex numbers is to multiply
the numerator and the denominator by it's complex conjugate, as this will make the 
denominator real. Applying this trick:
$$c + di = \frac{1}{a + bi} = \frac{a - bi}{a - bi} \cdot \frac{1}{a + bi} = \frac{a}{a^2 + b^2} - \frac{b}{a^2 + b^2}i$$
From comparing the real and imaginary parts of the left and right hand sides above:
$$c = \frac{a}{a^2 + b^2} \land d= \frac{b}{a^2 + b^2}$$
Note that the solution lies on the same line as $\overline{z}$ and it's magnitude is 
the reciprocal of the magnitude of $z = a + bi$.

<!-- ### Geometry
Complex numbers induce a rotation by the angle of the complex number and a scaling of it's magnitude to any number on which it is multiplied. If we let $z = a + bi$, then we would like to create a number $1/z$ which rotates $z$ onto the real line and scales $z$ by the reciprocal of it's magnitude so that $z \frac{1}{z} = 1$. To construct such a number we can use the fact that the complex conjugate of $z = a + bi$, that is $\overline{z} = a - bi$ has the negative of $z$'s angle with the real axis.
![Complex Conjugate](/LADR/Chapter1/ex1a_complex_conj.png "Image title")
Therefore $1/z$ lies on the line from the origin in the complex plane to $\overline{z}$ - this is exactly the line which rotates $z$ onto the real axis.
For $1/z$ to have the inverse magnitude of $z$ we scale $\overline{z}$ to have magnitude $1$ and then divide by the magnitude of $z$, that is (note from the figure above that $|z| = |\overline{z}|$): 
$$c + di = \frac{1}{z} = \frac{\overline{z}}{|z||\overline{z}|} = \frac{\overline{z}}{|z||z|} = \frac{\overline{z}}{|z||z|} = \frac{a - bi}{a^2 + b^2} = \frac{a}{a^2 + b^2} - \frac{b}{a^2 + b^2}i$$ -->



