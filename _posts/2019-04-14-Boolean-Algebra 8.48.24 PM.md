---
layout: post
title: "Boolean Algebra"
subtitle: "Formulae with Proofs"
date: 2019-04-14 19:03:00 +0900
author: "zangsy"
tags:
    - Digital Circuits
---

> 1. A, B and C in the follwoing are all binary.
>
> 2. ¬ means not.



- **OR rules**
  - A + 1 = 1​
  - A + 0 = A​
  - A + A = A

---

- **AND rules**
  - A 1 = A​
  - A 0 = 0
  - A A = A

---

- **Commutative**
  - A + B = B + A​
  - A B = B A

---

* **Associative**
  * (A + B) + C = A + (B + C)​
  * (A B) C = A (B C)​

---

* **Distributive**

  * A (B + C) = A B + A C​

  * (A + B) (A + C) = A + B C​

    * > (A + B) (A + C) = A A + A C + B A + B C = A + A C + B A + B C = A (1 + C + B) + B C = A 1 + B C = A + B C

---

* **Complements**
  * A + $$\vec{A}$$ = 1
  * A ¬A = 0​

---

* **Absorption**

  * A + A B = A

    * > A + A B = A (1 + B) = A 1 = A​

  * A + ¬A B = A + B​

    * > A + ¬A B = A + A B + ¬A B = A + B (A + ¬A) = A + B 1 = A + B​

  * A (A + B) = A​

    * >A (A + B) = A (A + ¬A B) = A A + A ¬A B = A + 0 B = A​

  * A (¬A + B) = A B​

---

* **Reduction**

  * A B + ¬A B = B​	

  * (A + B) (¬A + B) = B​

    * > (A + B) (¬A + B) = A ¬A + A B + B ¬A + B B = 0 + B (A + ¬A) + B = B 0 + B = B​

---

* **De Morgan's Law**
  * ¬A + ¬B = ¬(A B)
  * ¬A ¬B = ¬(A + B)