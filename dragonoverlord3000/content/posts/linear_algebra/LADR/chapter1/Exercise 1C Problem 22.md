---
title: "Exercise 1C Problem 22"
date: 2022-06-24T15:29:02+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 22 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose 
$$U = \lbrace (x,y,x+y,x-y,2x) \in \mathbb{F}^5 | x,y \in \mathbb{F} \rbrace$$
Find three subspaces $W_1, W_2, W_3$ of $\mathbb{F}^5$, none of which equals $\lbrace 0 \rbrace$, such that $\mathbb{F}^5 = U \oplus W_1 \oplus W_2 \oplus W_3$.

## Solution
We saw in [P1C21](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-21/) that $U \oplus W = \mathbb{F}^5$ if $W = \lbrace (0,0,x,y,z) \in \mathbb{F}^5 | x,y,z \in \mathbb{F} \rbrace$. But clearly $W = W_1 \oplus W_2 \oplus W_3$ if:
$$W_1 = \lbrace (0,0,x,0,0) \in \mathbb{F}^5 | x \in \mathbb{F} \rbrace$$ 
$$W_2 = \lbrace (0,0,0,x,0) \in \mathbb{F}^5 | x \in \mathbb{F} \rbrace$$ 
$$W_3 = \lbrace (0,0,0,0,x) \in \mathbb{F}^5 | x \in \mathbb{F} \rbrace$$
And by [P1C17](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-21/) plus [P1C21](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-21/) we therefore see that: 
$$\mathbb{F}^5 \stackrel{P1C21}{=} U \oplus W  = U \oplus (W_1 \oplus W_2 \oplus W_3) \stackrel{P1C17}{=} U \oplus W_1 \oplus W_2 \oplus W_3$$














