# IndexOutOfBoundsException in Java
This repository demonstrates a common Java error: the IndexOutOfBoundsException.  The `bug.java` file contains code that attempts to access an array element beyond its bounds.  The `bugSolution.java` file provides a corrected version.

**Problem:** The original code tries to access `arr[5]` in an array of size 5.  Java arrays are zero-indexed, meaning valid indices range from 0 to 4. Attempting to access index 5 results in an `IndexOutOfBoundsException`.

**Solution:** The solution involves ensuring that array access is always within the valid index range (0 to array.length - 1).  The solution demonstrates proper bounds checking.