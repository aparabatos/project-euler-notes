# Problem 2 - Even Fibonacci Numbers

## Idea
Find the sum of all even numbers in the Fibonacci sequence that do not exceed
four million. The Fibonacci sequence starts with the two numbers 1 and 2 in this
case, and each following term is the sum of the previous two numbers.

## Approach
1. Declare the first two numbers `n1` and `n2`.

2. If `n2` is even add it to the sum.

3. Continue the loop until `n2 > 4000000`, executing step 2 every iteration

## Insights
* Loops make series sums very easy to understand, and in some situations, looping
through the series is the only possible way

## Reflections
This Approach taught me to write a simple loop with as few steps as possible.

