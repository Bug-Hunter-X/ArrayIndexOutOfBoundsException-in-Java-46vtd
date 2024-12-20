# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element outside the valid range, leading to this exception.  The `bugSolution.java` file provides a corrected version.

## Running the code

1.  Save `bug.java` and `bugSolution.java`.
2. Compile and run using a Java compiler (like the one included in the JDK):
   ```bash
   javac bug.java
   java MyClass
   javac bugSolution.java
   java MyClassSolution
   ```

## Learning Points

-  Understanding array bounds in programming is crucial to avoid this type of error.
-  Careful attention to loop conditions and array indexing is essential for writing robust code.
-  Always double-check array access to prevent `ArrayIndexOutOfBoundsException`. 