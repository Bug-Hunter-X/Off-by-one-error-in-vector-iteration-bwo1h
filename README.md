# Off-by-one Error in Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs because the loop condition `i <= vec.size()` attempts to access an element beyond the valid range of the vector.  Vectors are zero-indexed, so the last valid index is `vec.size() - 1`.

The `bug.cpp` file contains the erroneous code. The `bugSolution.cpp` file shows the corrected code. 