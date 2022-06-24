---
title: "Exercise 1C Problem 13"
date: 2022-06-21T15:20:21+02:00
description: "Linear Algebra Done Right - Exercise 1C Problem 13 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove that the union of three subspaces of $V$ is a subspace of $V$if and only if one of the subspaces is contained in the other.

## Solution
<!-- Inspiration: https://math.stackexchange.com/a/3859776/832015 -->

$(\leftarrow)$ The case where one of the three subsets contain one of the other was handled in [P1C12](https://dragonoverlord3000.github.io/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-12/). Therefore we can assume that the three subspaces, denoted $U_1$, $U_2$ and $U_3$ from here on out, each have elements that aren't in the union of the other two sets - see this figure:
![Venn diagram](/LADR/Chapter1/P1C13_venn.png) 
Let now $v \in U_2$ be such that $v$ $\cancel{\in}$ $U_3$ and let $w \in U_3$ such that $w$ $\cancel{\in}$ $U_2$ and choose nonzero $a,b \in \mathbb{F}$ such that $a - b = 1$. 

Suppose now, BWOC, that $av + w \in U_2$, then $w = -av + (av + w) \in U_2$ because $U_2$ is a subspace, but this is a contradiction since $w$ $\cancel{\in}$ $U_2$. And by a similar argument we get $bv + w$ $\cancel{\in}$ $U_3$. Thus, for $U_1 \cup U_2 \cup U_3$ to be a subspace we must have $av + w \in U_1$ and $bv + w \in U_1$.

Because $U_1$ is a subspace $v = (av + w) - (bv + w) \in U_1$, thus any vector $v \in U_2$ such that $v$ $\cancel{\in}$ $U_3$ is in $U_1$ - and by a simmilar argument any $w \in U_3$ such that $w$ $\cancel{\in}$ $U_2$ will also be in $U_1$. If $U_2 \cap U_3 = \lbrace 0 \rbrace$, then any $v \in U_2$ will have the property $v$ $\cancel{\in}$ $U_3$ and therefore $v \in U_1$ and similar for any $w \in U_3$, thus $U_2 \subset U_1$ and $U_3 \subset U_1$.

If on the other hand $U_2 \cap U_3 \neq \lbrace 0 \rbrace$, then we can let $u \in U_2 \cap U_3$ and $w \in U_3$ with $w$ $\cancel{\in}$ $U_2$ $\to$ $w \in U_1$. If $u + w \in U_2 \cap U_3$, then $w = (u + w) - u \in U_2 \cap U_3$, because $U_2 \cap U_3$ is a subspace as per [P1C10](http://localhost:1313/posts/linear_algebra/ladr/chapter1/exercise-1c-problem-10/), but this is a contradiction because $w$ $\cancel{\in}$ $U_2$. 
Therefore, for $U_1 \cup U_2 \cup U_3$ to be a subspace we must have $u + w \in U_1 \cup U_3$, but $u + w \in U_3$ with $u + w$ $\cancel{\in}$ $U_2$ implies $u + w \in U_1$ and thus we conclude $U_2 \cap U_3 \subset U_1$.

To summarize:
1. If $v \in U_2$ and $v$ $\cancel{\in}$ $U_3$, then $v \in U_1$
2. If $v \in U_3$ and $v$ $\cancel{\in}$ $U_2$, then $v \in U_1$
3. If $v \in U_2 \cap U_3$, then $v \in U_1$

Therefore $U_2, U_3 \subset U_1$ as we wanted to show.

$(\rightarrow)$ If $U_2 \cup U_3 \subset U_1$, then $U_1 \cup U_2 \cup U_3 = U_1$ which is a subspace.






## Inspiration

JeffW89, [Prove that the union of three subspaces of $V$ is a subspace iff one of the subspaces contains the other two.](https://math.stackexchange.com/users/200928/jeffw89), URL (version: 2022-01-31): [MSE](https://math.stackexchange.com/q/3859776)





















