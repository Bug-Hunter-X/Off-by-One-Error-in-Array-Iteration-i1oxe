# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition `i <= arr.length` attempts to access an element beyond the array's bounds.  This leads to an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the erroneous code, while `bugSolution.java` provides the corrected version.  Understanding this error is crucial for writing robust and error-free Java programs.