---
title: "Exercise 1C Problem 24"
date: 2022-06-24T16:00:44+02:00
math: true
draft: true
---

## Problem
A function $f: \mathbb{R} \to \mathbb{R}$ is called *even* if
$$f(-x) = f(x)$$
for all $x \in \mathbb{R}$. A function $f: \mathbb{R} \to \mathbb{R}$ is called *odd* if
$$f(-x) = -f(x)$$
for all $x \in \mathbb{R}$. Let $U_e$ denote the set of real-valued even functions on $\mathbb{R}$ and $U_o$ denote the set of real-valued odd functions on $\mathbb{R}$. Show that $\mathbb{R}^\mathbb{R} = U_e \oplus U_o$

## Solution
Any function $f: \mathbb{R} \to \mathbb{R}$ can be decomposed into an even and an odd part as follows:
$$f_{e}(x) =  \frac{f(x) + f(-x)}{2}$$
$$f_{o}(x) =  \frac{f(x) - f(-x)}{2}$$
Where $f_{e}(x) = f_{e}(-x)$ and $f_{o}(-x) = -f_{o}(x)$ and also:
$$f_e(x) + f_o(x) = \frac{f(x) + f(-x)}{2} + \frac{f(x) - f(-x)}{2} = f(x)$$
Thus any function $f \in \mathbb{R}^\mathbb{R}$ can be written as $f_e + f_o$ where $f_e \in U_e$ and $f_o \in U_o$ and since we clearly have $U_e \cap U_o = \lbrace 0 \rbrace$, we must have that $\mathbb{R}^\mathbb{R} = U_e \oplus U_o$.












