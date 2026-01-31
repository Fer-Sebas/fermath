---
title: Vector Space
draft: false
tags:
  - AlgebraicStructure
  - VectorSpace
---
# Overview
A vector space is an **[algebraic structure](Algebraic%20Structures.md)** defined as a set $\large V$ together with two operations called **vector addition** (which combines two vectors) and **scalar multiplication** (which scales a vector by a scalar).

A vector space is always defined **over a [field](Field)** of scalars.

# Vector
A vectors is simply an **element** of a vector space $(\large v∈V)$. 

There is nothing intrinsically “**vector-like**” about an object by itself.  

Anything that participates correctly in vector addition and scalar multiplication qualifies as a vector.
# Vector Addition 
Vector addition takes two vectors from the same space and returns another one.

$\Large +: V \times V \to V$

Vector addition must satisfy the following properties:
* **[[Closure]]**: adding two vectors produces another vector.
  <br>$\Large \forall u,v \in V, \space u + v \in V$<br><br>
  
* **[[Commutativity]]**: the order of addition does not alter the result.
  <br>$\Large \forall u,v \in V, \space u + v = v + u$.<br><br>
  
* **[[Associativity]]**: grouping of addition does not matter.
* **[Invertible](Inverse)**: every vector has an additive inverse.
* **[[Identity]]**: there is a vector that changes nothing when added (think adding zero).

# Scalar Multiplication
Scalar multiplication scales a vector by a scalar.

$\Large a \cdot v \in V \space\space\space\space for \space a \in F, v \in V$

Scalar multiplication must satisfy the following properties:
* **[[Associativity]]**: scaling by one scalar and then another is the same as scaling by their product.
* **[[Identity]]**: multiplying a vector by the scalar one leaves it unchanged (think multiplying by 1).
* **[[Distributivity]]**: over vector addition and over scalar addition.