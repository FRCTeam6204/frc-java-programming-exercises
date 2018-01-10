# Exercises – Intermediate Java Programming
These problems should be completable after finishing the Java Basics exercises, although may need a bit of searching online or reading of documentation to solve.

##### 1. Rewrite the sum function from [Java Basics](java-basics.md) using recursion.
Helpful links:
* [Recursion Basics](http://www.dummies.com/programming/java/what-is-recursion-in-java-programming/)
* [Recursion in Java](https://www.javatpoint.com/recursion-in-java)

##### 2. Create a Range class.
This class should take two integers, a minimum and a maximum. It should provide a method, `map`, which takes a [lambda function](https://beginnersbook.com/2017/10/java-lambda-expressions-tutorial-with-examples/) as an argument, and returns an array with that function applied to each number between the minimum and the maximum (inclusive). For example:
```java
Range rng = new Range(1, 5);
rng.map(n -> n + 1);
// rng.map should return {2, 3, 4, 5, 6}
```

Use this code for the method body to get you started:
```java
import java.util.function.IntUnaryOperator;

public int[] map(IntUnaryOperator f) {
  // Usage: f.applyAsInt(5) is the same as f(5)
}
```

##### 3. Write a function to calculate the sum of the squares in a certain range.
*Hint: You can utilise your solution to the previous problems to solve this one.*
