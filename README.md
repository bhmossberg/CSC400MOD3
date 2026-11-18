# CSC400MOD3 – Big-Oh Analysis Exercises

**CSU Global CSC400, Module 3.** This repository holds only the exercise prompts below. No solution code or write-up has been committed yet, apart from a Java `.gitignore`.

## Assignment

Complete the following exercises. For each exercise, show your work and all the steps taken to determine the Big-Oh for each problem. Partial points cannot be awarded without showing work.

### Exercise 1
What is the Big-Oh of the following computation?

```java
int sum = 0;
for (int counter = n; counter > 0; counter = counter - 2)
      sum = sum + counter;
```

### Exercise 2
Suppose your implementation of a particular algorithm appears in Java as follows:

```java
for (int pass = 1; pass <= n; pass++)
{
	for(int index  = 0; index < n; index++)
	{
		for(int count = 1; count < 10; count++)
		{
			. . . 

		} //end for
	} // end for
} //end for
```

The algorithm involves an array of "n" items. The previous code shows only the repetition in the algorithm, but it does not show the computations that occur within the loops. Those computations, however, are independent of "n." What is the order of the algorithm?

### Exercise 3
Consider two programs, A and B. Program A requires 1000 x n^2 operations and Program B requires 2^n operations. For which values of n will Program A execute faster than Program B?

### Exercise 4
Consider an array of length "n" containing unique integers in random order and in the range 1 to n + 1. For example an array of length 5 would contain 5 unique integers selected randomly from the integers 1 through 6. Thus the array might contain 3 6 5 1 4. Of the integers 1 through 6, notice that 2 was not selected and is not in the array. Write Java code that finds the integer that does not appear in such an array. Explain the Big-Oh in your code.

## Concepts covered
- Counting loop iterations to find growth rates
- Dropping constant factors and lower-order terms in Big-Oh notation
- Comparing polynomial growth (n²) with exponential growth (2ⁿ)
- Analyzing the time complexity of a search algorithm you write yourself
