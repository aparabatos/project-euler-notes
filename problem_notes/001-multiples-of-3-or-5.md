# Problem 1 - Multiples of 3 or 5

## Idea
Find the sum of all natural numbers below _N_ that are multiples of 3 or 5. This
reduces to a sum of two arithmetic progression, with adjustment for
double-counted for multiples of 15.

## Aproach
1. Use the formula for the sum of an arithmetic progression:
$S = k \cdot \frac{a_1 + a_k}{2}$ where $k$ is th number of terms.

2. Compute sums for multiples of 3, multiples of 5, then subtract multiples of
15\.

## Insights
* This can be use to any set of integers

## Reflection
This approach taught me to stop before brute-forcing. A direct approach like
this I found is cleaner and faster. It also reminded me the importance of
checking for overlap.

