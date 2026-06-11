---
title: "Stabilizer Codes"
permalink: /stabilizer-codes/
author_profile: true
---

# Stabilizer Codes

Before reading this page, see [Pauli Groups]({{ site.baseurl }}/pauli-groups/).

---

## Definition 1: Stabilizer Code {#def-stabilizer-code}

A **stabilizer code** is a subspace

\[
C \subseteq (\mathbb{C}^2)^{\otimes n}
\]

defined as the joint \(+1\)-eigenspace of an abelian subgroup

\[
S \subseteq P_n.
\]

We refer to this as [Definition 1](#def-stabilizer-code).

---

## Lemma 1: Simultaneous Diagonalization {#lem-simultaneous-diagonalization}

Let \(S\) be an abelian subgroup of \(P_n\). Then the elements of \(S\) are simultaneously diagonalizable.

**Proof.**  
Each Pauli operator is normal, and the elements of \(S\) commute. Therefore they are simultaneously diagonalizable. \(\square\)

---

## Theorem 1: Existence of Stabilizer Codes {#thm-existence}

Let \(S \subseteq P_n\) be abelian and suppose \(-I \notin S\). Then the joint \(+1\)-eigenspace of \(S\) is nonzero.

**Proof.**  
By [Lemma 1](#lem-simultaneous-diagonalization), the operators in \(S\) are simultaneously diagonalizable. Since \(-I \notin S\), the \(+1\)-eigenspace is consistent and defines a nonzero subspace. \(\square\)

---

## Equation Example {#eq-projector}

The stabilizer projector is

\[
\Pi_S = \frac{1}{|S|}\sum_{g \in S} g.
\tag{1}
\]

This is the projector onto the code space. We refer to it as Equation [(1)](#eq-projector).

---

## References

1. Nielsen, M. A. and Chuang, I. L., *Quantum Computation and Quantum Information*.
2. Gottesman, D., *Stabilizer Codes and Quantum Error Correction*.
3. Preskill, J., *Lecture Notes on Quantum Computation*.

---

[Back to Contents]({{ site.baseurl }}/qec/)  
[Next: CSS Codes]({{ site.baseurl }}/css-codes/)
