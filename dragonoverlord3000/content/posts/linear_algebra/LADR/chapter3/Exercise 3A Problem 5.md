---
title: "Exercise 3A Problem 5"
date: 2022-06-28T14:42:28+02:00
description: "Linear Algebra Done Right - Exercise 3A Problem 5 - Solution"
tags: ["LADR", "linear algebra", "math"]
categories: ["Linear Algebra"]
math: true
showtoc: true
env: production
---

## Problem
Prove the assertion in 3.7.

## Solution
Let $T, S, S^\prime \in \mathcal{L}(V,W)$, then:

1. Commutativity

$$(T + S)(v) \stackrel{D3.6}{=} Tv + Sv \stackrel{D1.19}{=} Sv + Tv \stackrel{D3.6}{=} (S + T)(v)$$

2. Associativity

$$((T + S) + S^\prime)(v) \stackrel{D3.6}{=} (T + S)(v) + S^\prime(v) $$
$$\stackrel{D3.6}{=} (T(v) + S(v)) + S^\prime(v) \stackrel{D1.19}{=} T(v) + (S(v) + S^\prime(v))$$
$$\stackrel{D3.6}{=} T(v) + (S + S^\prime)(v) \stackrel{D3.6}{=} (T + (S + S^\prime))(v)$$

And if we let $a, b \in \mathbb{F}$, then:

$$((ab)T)(v) \stackrel{D3.6}{=} (ab)(Tv) \stackrel{D1.19}{=} a(b(Tv)) \stackrel{D3.6}{=} a(bT)(v)$$

3. Additive identity

The zero-map '$0(v) = 0$' described in Example 3.4. Has the property that: 
$$Tv \stackrel{D1.19}{=} 0(v) + T(v) \stackrel{D3.6}{=} (0 + T)(v)$$ 
$$\stackrel{(1)}{=} (T + 0)(v) \stackrel{D3.6}{=} T(v) + 0(v) \stackrel{D1.19}{=} Tv$$

4. Additive inverse

Define $T^\prime v = -Tv$, then $-Tv \in \mathcal{L}(V,W)$ as per definition 1.19. Then by the linearity of $T$, we have $T^\prime (\lambda v + \mu u) = -T(\lambda v + \mu u) \stackrel{D3.2}{=} \lambda (-Tv) + \mu (-Tu) = \lambda T^\prime + \mu T^\prime$, that is, linearity of $T^\prime$.

Therefore $T^\prime \in \mathcal{L}(V,W)$ exists with the property $(T + T^\prime)(v) \stackrel{D3.6}{=} Tv + T^\prime v = Tv - Tv = 0$.

5. Multiplicative identity

$$(1T)(v) \stackrel{D3.6}{=} 1(Tv) \stackrel{D1.19}{=} = Tv$$

6. Distributive properties

Let $a,b \in \mathbb{F}$, then:
$$(a(T + S))(v) \stackrel{D3.6}{=} a(T + S)(v) \stackrel{D3.6}{=} a(Tv + Sv) \stackrel{D1.19}{=} aTv + aSv$$
$$\stackrel{D3.6}{=} (aT)(v) + (aS)(v) \stackrel{D3.6}{=} (aT + aS)(v)$$

And also:
$$((a + b)(T))(v) \stackrel{D3.6}{=} (a + b)(Tv) \stackrel{D1.19}{=} a(Tv) + b(Tv)$$ $$\stackrel{D3.6}{=} (aT)(v) + (bT)(v)$$



