# PL Junior

PL Junior is a tradition of Northeastern's Programming Research Laboratory since ????. It is a weekly meeting of mostly first and second year phd students studying and discussing a variety of topics in programming languages research. However, anyone interested in learning PL topics is welcome.

## Participants
+ Artem Pelenitsyn


## Schedule

### Sept 17

**Topic**: Intro to CPS  
**Guest lecturer**: William Bowmen  
**Outline of the lecture**:  
1. What is CPS?
   Continuation-Passing style, and transformations from direct style in CPS.
2. Why CPS?
   - Making control-flow explicit
     Used in concurrent programming, such as GUI programming (call-backs are
     continuations).
   - Making evaluation order explicit
     Need to force evaluation to a value in CBN, or force CBN on a CBV machine.
   - Internalize the evaluation context
     To express control effects internally in the language.
   - A translation that makes values and computation distinct.
     Bad news: code is not actually data.
2. Untyped CPS
   - "Plotkin's translation"
    - CBV
    - CBN
   - translating the evaluation context directly.
   - machine semantics
   - naturality
3. Typed CPS
   - value vs computation vs programs (and their types)
   - "Double negation"
   - Fixed answer type
     - Actually, this is double negation to.
   - Locally polymoprhic answer type
     - Actually, this is double negation to.

The following is *optional*:  
+ Papers to read:
  - Gordon Plotkin. Call-by-name, call-by-value, and the λ-calculus. Theoretical Computer Science: 1975  
   http://homepages.inf.ed.ac.uk/gdp/publications/cbn_cbv_lambda.pdf
    + Ben Greenman's summary of this paper:  
     http://www.ccs.neu.edu/home/types/resources/notes/call-by-name-call-by-value/extended-intro.pdf

+ A bunch of resources on good pedagogical presentations of CPS:  
 http://lists.seas.upenn.edu/pipermail/types-list/2018/002000.html

+ Essentials of Programming Languages, Chapter 6

### Sept 24 (ICFP week)

Topic: **ANF/continuations**  
Papers to read for this week:  
+ Reasoning about Programs in Continuation Passing Style:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.26.7234&rep=rep1&type=pdf

Progress: Page 1 -- 4
Notes:


Papers that will follow later in this series:
+ The Essence of Compiling with Continuations   https://slang.soe.ucsc.edu/cormac/papers/pldi93.pdf
+ Compiling with Continuations, Continued   https://www.microsoft.com/en-us/research/wp-content/uploads/2007/10/compilingwithcontinuationscontinued.pdf
+ Compiling without Continuations   https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/compiling-without-continuations.pdf

### Oct 1

Topic: **ANF/continuations** (Continued)  
Papers:
+ Reasoning about Programs in Continuation Passing Style:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.26.7234&rep=rep1&type=pdf

Progress: Page 5 -- 6  
Notes:


### Oct 8 (Columbus Day)

Topic: **ANF/continuations** (Continued Continued)  
Papers:
+ Reasoning about Programs in Continuation Passing Style:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.26.7234&rep=rep1&type=pdf

Progress:  
Notes:

### Oct 15

Lead:
Topic:  
Papers:  
+  

Progress:  
Notes:

### Oct 22

Lead:
Topic:  
Papers:  
+  

Progress:  
Notes:

### Oct 29

Lead:  
Topic:   
Papers:    
+  

Progress:  
Notes:


### Nov 5 (SPLASH week)

### Nov 12 (Veteran's Day?)

### Nov 19 (Thanksgiving week?)

### Nov 26 (Monday after Thanksgiving)

### Dec 3

### Dec 10 (last week of classes)  




The following is topics brought up for this semester's meetings:

## At the First meeting...

**Voting**  
8 TAPL / ATAPL  
6 Coq  
8 Compiling with Continuations / ANF  
5 Staging  
7 Types papers  
5 Static analysis  


**Textbook exercises**  

Later chapters of TAPL  
Advanced TAPL  
Software Foundations (later books/volumes)  
Certified Programming with Dependent Types  


**Summer schools**

OPLSS  
DeepSpec  

**Reading papers / textbooks**

Compiling with Continuations / without Continuations  
ANF  
Staging  
Unifying Subtyping and Polymorphism  
Familia? (OOPSLA 2017)  
Static analysis  
Type-preserving compilation  


**Conference talks / lectures**

Compilers, inlining  
Intermediate representations (compilers)


Maybe schedule practice talks / writing feedback separately
