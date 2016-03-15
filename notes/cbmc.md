# CBMC

CBMC is a Bounded __Model Checker__ for C and C++ programs.  
http://www.cprover.org/cbmc/  

The __assertion__ generator can generate assertions for the verification of the following properties:

- __Buffer overflows__
    - For each array access, check whether the upper and lower bounds are violated.
- __Pointer safety__
    - Search for NULL-pointer dereferences or dereferences of other invalid pointers.
- __Division by zero__
    - Check whether there is a division by zero in the program.
- __Not-a-Number__
    - Check whether floating-point computation may result in NaNs.
- __Unitialized local__
    - Check whether the program uses an uninitialized local variable.
- __Data race__
    - Check whether a concurrent program accesses a shared variable at the same time in two threads.
