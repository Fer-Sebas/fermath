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
Vector addition takes two vectors and returns another one.

$\Large +: V \times V \to V$

Vector addition must satisfy the following properties:
* **[[Closure]]**: adding two vectors produces another vector inside the same space.
  <br><br>$\large \forall u,v \in V, \space u + v \in V$<br><br>
  
* **[[Commutativity]]**: the order of addition does not alter the result.
  <br><br>$\large \forall u,v \in V, \space u + v = v + u$.<br><br>
  
* **[[Associativity]]**: grouping of addition does not matter.
    <br><br>$\large \forall u,v,w \in V, \space (u + v) + w = u + (v + w)$.<br><br>
* **[Invertible](Inverse)**: every vector has an additive inverse.
    <br><br>$\large v+(-v) = (-v)+v=0$.<br><br>
* **[[Identity]]**: there is a vector that changes nothing when added (think adding zero).
    <br><br>$\large \forall v \in V, \space v + 0 = 0 + v = v$.<br><br>

# Scalar Multiplication
Scalar multiplication scales a vector by a scalar.

$\Large \cdot: F \times V \to V$

Scalar multiplication must satisfy the following properties:
* **[[Associativity]]**: scaling by one scalar and then another is the same as scaling by their product.
  <br>$\large \forall a,b \in F, \forall v \in V, \space\space (ab) \cdot v = a \cdot (b \cdot v)$.<br><br>
* **[[Identity]]**: multiplying a vector by the scalar one leaves it unchanged (think multiplying by 1).
  <br>$\large \forall v \in V = 1 \cdot v = v$.<br><br>
* **[[Distributivity]]**: over vector addition and over scalar addition.
  <br>$\large \forall a \in F, \forall u,v \in V, \space\space a \cdot (u +v) = a \cdot u + a \cdot v$.<br><br>
    <br>$\large \forall a, b \in F, \forall v \in V, \space\space (a +b) \cdot v = a \cdot v + b \cdot v$.<br><br>