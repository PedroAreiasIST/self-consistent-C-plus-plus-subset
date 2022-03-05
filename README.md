# self-consistent-C-subset

---------------------------------------------------------
A self-consistent C++ subset for programming productivity
---------------------------------------------------------

-------------------
Big-picture choices:
-------------------
  In descending order, we focus on:
  
1) Consistency of writing.
2) Syntax conciseness and clarity.
3) Programming productivity.
4) Source code reading cleanliness.
5) Facilitated use of auto-completion.
6) Unified forms for variable declaration, initialization and function definition.
7) Performance.
8) Refinement of established solutions.

-----------------------
We have no respect  for:
-----------------------

1) Safety.
2) Encapsulation.
3) Polymorphism.
4) OO.
5) Tricks and smart solutions.
6) Fashion.

---------
Decisions:
---------

1) Only structs, no classes.
2) No protected/private member variables.
3) Very limited use of member functions.
4) Very limited use of operator overloading.
5) Use of useful C-style features and mechanisms.
6) Use of RAII for managing structs.
7) Extensive use of the rule of Zero.
8) Use of nested namespaces for identifying functions in a tree-like form.
9) Extenive use of template functions and structs.
10) Use of linear containers. No STL.
