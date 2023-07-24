# self-consistent-C++-subset
# a motorcycle rider approach

---------------------------------------------------------
A self-consistent C++ subset for programming productivity
---------------------------------------------------------
-------------------
Big-picture choices:
-------------------
  In descending order, we focus on:
  
1) Consistency of writing.
2) Balance between syntax conciseness and clarity.
3) Programming productivity.
4) Source code cleanliness.
5) Facilitated use of auto-completion.
6) Unified rules for variable declaration, initialization and function definition.
7) Performance of execution and compilation.
8) Refinement of C and C++ established solutions.

----------------
We have opinions:
----------------

1) Safety slows everything.
2) Encapsulation is a hoax.
3) std algorithm and std execution are helpful.
4) Polymorphism based on virtual functions is childish.
5) Most member functions should be replaced by free-standing ones.
6) Tricks and smart solutions are usually not intelligent.
7) Coding ego is not your amigo.

---------
Decisions:
---------

1) A base-library with essentials is being constructed.
2) We only use trivial and partially standard layout structs.
3) Protected and private members are out-of-the-question.
4) A very limited use of member functions is allowed.
5) A very limited use of operator overloading is allowed.
6) C is still good. We favor use of useful C-style features and mechanisms.
7) Structs follow aggregate initialization. 
8) We favor RAII for managing structs.
9) We favor the use of the rule of Zero.
10) Namespaces are favored for identifying functions in a tree-like form.
11) We favor an extensive use of template functions and structs.
12) We adopt linear containers. 
13) The only allowable function return values are of intrinsic types.
14) The use of MACROS is encouraged, if locally defined.
