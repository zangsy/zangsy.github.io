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



- **OR rules**
  
  
  $$
  \begin{aligned}
  A + 1 &= 1 \\ 
  \\
  A + 0 &= A \\ 
  \\
  A + A &= A \\
  \end{aligned}
  $$

---

- **AND rules**
  
  
  $$
  \begin{aligned} 
  A1 &= A \\ 
  \\
  A0 &= 0 \\ 
  \\
  AA &= A \\
  \end{aligned}
  $$

---

- **Commutative**
  
  
  $$
  \begin{aligned} 
  A+B &= B+A \\
  \\
  AB &= BA \\
  \end{aligned}
  $$

---

* **Associative**
  
  
  $$
  \begin{aligned} 
  (A+B)+C &= A+(B+C) \\
  \\
  (AB)C &= A(BC) \\
  \end{aligned}
  $$

---

* **Distributive**

  
$$
  \begin{aligned} 
A(B+C) &= AB+AC \\
  \\
  (A+B)(A+C) &= A+BC \\
  &= AA+AC+BA+BC \\ 
  &= A+AC+BA+BC \\ 
  &= A(1+C+B)+BC \\
  &= A1+BC \\ 
  &= A+BC
  \end{aligned}
  $$

---

* **Complements**
  
  
  $$
  \begin{aligned}
  A+\overline{A} &= 1 \\
  \\
  A\overline{A} &= 0 \\
  \end{aligned}
  $$

---

* **Absorption**

  
$$
  \begin{aligned}
A+AB &= A \\
  &= A(1+B) \\
&= A1 \\
  &= A \\
\\
  A+\overline{A}B &= A+B \\
&= A+AB+\overline{A}B \\
  &= A+B(A+\overline{A}) \\
&= A+B1 \\
  &= A+B \\
  \\
  A(A+B) &= A \\
  &= A(A+\overline{A}B) \\
  &= AA+A\overline{A}B \\
  &= A+0B \\
  &= A \\
  \\
  A(\overline{A}+B) &= AB \\
  \end{aligned}
  $$

---

* **Reduction**

  
$$
  \begin{aligned}
AB+\overline{A}B &= B \\
  \\
  (A+B)(\overline{A}+B) &= B \\
  &= A\overline{A}+AB+B\overline{A}+BB \\
  &= 0+B(A+\overline{A})+B \\
  &= B0+B \\
  &= B \\
  \end{aligned}
  $$

---

* **De Morgan's Law**
  
  
  $$
  \begin{aligned}
  \overline{A}+\overline{B} &= \overline{(AB)} \\
  \\
  \overline{A}\overline{B} &= \overline{(A+B)} \\
  \end{aligned}
  $$