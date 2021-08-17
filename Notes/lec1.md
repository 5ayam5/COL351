---
geometry:
- top=25mm
- left=20mm
- right=20mm
- bottom=30mm
documentclass: extarticle
fontsize: 12pt
numbersections: true
---

# Lecture 1 (Introduction)

## Course Policy
1. Quizzes - 15% (suprise/announced)
2. Assignments - 20% (typed and groups of size $\leq 2$)
3. Minor - 30%
4. Major - 30%
5. Attendance - 5%
6. Class participation (if boderline of grade change)

## Asymptotic Bound  
1. $T(n) = O(f(n))$ if $\exists c, k \in \mathbb{R}$ such that $T(n) \leq c \cdot f(n) \forall n \geq k$
2. $T(n) = \Omega (g(n))$ if $\exists c, k \in \mathbb{R}$ such that $T(n) \geq c \cdot g(n) \forall n \geq k$
3. $T(n) = \Theta (h(n))$ if $T(n) = O(h(n))$ and $T(n) = \Omega (h(n))$

#### Task
Prove that ${log}(n) = O(n^\varepsilon)$ $\forall$ $\varepsilon > 0$

### Problem  
Given a histogram, find the maximum area of the rectangle that is present.

## Rest of the Lecture  
Discussing time complexities of merge-sort, Fibonacci - exponential vs *linear* (since for large $n$, the sum will not take constant time)

