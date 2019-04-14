---
layout: post
title: "Boolean Algebra"
subtitle: "Formulae with Proofs"
date: 2019-04-14 19:03:00 +0900
author: "zangsy"
tags:
    - Digital Circuits
---

> > A, B and C in the follwoing are all binary



- **OR rules**
  - $A + 1 = 1​$
  - $A + 0 = A$
  - $A + A = A$



- **AND rules**
  - $A1 = A$
  - $A0 = A$
  - $AA = A$



- **Commutative**
  - $A + B = B + A$
  - $AB = BA$



* **Associative**
  * $(A + B) + C = A + (B + C)$
  * $(AB)C = A(BC)$



* **Distributive**

  * $A(B + C) = AB + AC$

  * $(A + B)(A + C) = A + BC​$

    * > $(A + B)(A + C) = AA + AC + BA + BC = A(1 + C + B) + BC = A1 + BC = A + BC



* **Complements**
  * $A + \overline{A}= 1​$
  * $A\overline{A} = 0​$



* **Absorption**

  * $A + AB = A$

    * > $A + AB = A(1 + B) = A1 = A​$

  * $A + \overline{A}B = A + B$

    * > $A + \overline{A}B = A + AB + \overline{A}B = A + B(A + \overline{A}) = A + B1 = A + B$

  * $A(A + B) = A$

    * >$A(A + B) = A(A + \overline{A}B) = AA + A\overline{A}B = A + 0B = A$

  * $A(\overline{A} + B) = AB​$



* **Reduction**

  * $AB + \overline{A}B = B​$	

  * $(A + B)(\overline{A} + B) = B$

    * > $(A + B)(\overline{A} + B) = A\overline{A} + AB + B\overline{A} + BB = 0 + B(A + \overline{A}) + B = B0 + B = B$



* **De Morgan's Law**
  * $\overline{A} + \overline{B} = \overline{AB}$
  * $\overline{A}\overline{B} = \overline{A + B}$