---
title: "Exercise 2C Problem 13"
date: 2022-06-27T18:46:19+02:00
description: "Linear Algebra Done Right - Exercise 2C Problem 13 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Suppose $U$ and $W$ are both 4-dimensional subspaces of $\mathbb{C}^6$. Prove that there exist two vectors in $U \cap W$ such that neither of these vectors is a scalar multiple of the other

## Solution
By theorem 2.43, 2.38 and the fact that $U + W$ is a subspace of $\mathbb{C}^6$ by theorem 1.39:
$$6 = \dim \mathbb{C}^6 \geq \dim (U + W) = \dim U + \dim W - \dim U \cap W$$
$$= 4 + 4 - \dim U \cap W$$
Implying that $\dim U \cap W \geq 2$, therefore by the definition of dimension. there must exist two linearly independent vectors, a basis for $U \cap W$ which is a vector space as per [P1C10](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-10/). Therefore we can let $v_1,v_2 \in U \cap W$ be a basis for $U \cap W$ implying that the only solution to $a_1v_1 = a_2v_2$, for $a_1,a_2 \in \mathbb{C}$ is the trivial one.




