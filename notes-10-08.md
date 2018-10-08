The original Fischer transformation, $F$, is correct, but the presence of administrative redexes are undesirable.
Hence, modified Fischer CPS, $F2$, is introduced. $F2$ is a two-pass transformation in which
 - First pass marks the new lambda abstractions to identify administrative redexes and
 - Second pass reduces all administrative redexes.

The paper proves $F2$ is a total function meaning $F2$ is defined on all source terms and "correctly" CPS transforms them in finite amount of time using the Church-Rosser normal form theorem.

Plotkin proved some interesting theorems about the relation between reductions on source terms and CPS terms.
They revealed that $\beta$-reductions prove more equations on CPS terms that $\beta_v$-reductions prove on source terms.  
The paper tries to remedy this by proving
\[
\lambda_v A \vdash M = N \iff \lambda \beta \eta \vdash F2[M] = F2[N],
\]
where $A$ is a set of axioms needed for this equivalence or simulation between source and corresponding CPS programs to hold.
However, some complications to this problem is presented.
One example is a CPS term reduces to a term that contains an administrative redex and hence cannot be $F2[M]$ for any $M \in \Lambda$.
However, it is provably equal to a number of CPS terms, among which introduces the inverse of the term.
Inspired by this example, the authors proceed the following which will be presented in section 5.
- Definition of a one-pass CPS transformation equivalent to $F2$
- Inverse of CPS transformation and its relationship to the CPS transformations
- Set $A$, the derived axiom set, needed for the source language to have equivalent equations that CPS programs have
