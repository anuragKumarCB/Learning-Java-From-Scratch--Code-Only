# day0001

## 🚀 Problem  
Write and run the very first Java program in this series. 

## 💡 Approach

1. `public`: access modifier (makes the class accessible everywhere).  
2. `class`: everything in Java lives inside a class.  
3. **`File name vs Class name`**:  
   - If your file is named `Welcome.java`, then the class name **must** be `Welcome`.  
   - Otherwise, you’ll get a compilation error.  
4. **`What is System?`**:
    - System is a final class in the java.lang package.
    - It provides access to system-level resources, such as standard input (System.in), standard output (System.out), and standard error (System.err).
5. **`What is System.out?`**:
    - `out` is a public static field of the System class.
    - It is an instance of the PrintStream class.
    - By default, System.out points to the standard output stream (your console terminal).
    - So whenever we use System.out, we are really working with this PrintStream object.
6. **`Difference between print() and println()`**
    - `print()`: prints text without moving to the next line.
    - `println()`: prints text and then moves to the next line (equivalent to print("\n")).