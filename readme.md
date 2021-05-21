# DSA-V1

## Big O Notation

1. Constant time O(1)
   Constant time complexity is the "holy grail".
   No matter the size of your input, the algorithm will take the same amount of time to complete.
   Examples of O(1) algorithms are accessing an array item or performing basic arithmetic operations (e.g., adding 2 numbers).
   The following is an example of an algorithm with O(1) runtime complexity.

2. Logarithmic time O(log(n))
   Logarithmic time complexity (O(log n)) is the next
   best thing after constant time. While logarithmic time complexity algorithms
   do take longer with larger inputs, running time increases slowly. For
   instance, if myLogRunTimeAlgo takes 1 second to complete with an input of size
   10, when we increase our input by 10x to 100, the running time only grows to 2
   seconds. When we increase the input size to 1000, the time only grows to 3
   seconds. It is also characteristic of logarithmic algorithms that they cut the
   problem size in half each round through.{" "}

3. Polynomial time O(n^k)
   An algorithm with polynomial time complexity has a
   running time that would be some input size n raised to some constant power k.
   The easiest way to understand polynomial time complexity is with nested loops.
   An algorithm that requires 2 levels of looping over an input would be O(n^2)
   while one requiring 3 levels of looping would be O(n^3). In both cases, we
   have polynomial time complexity.

4. Exponential time O(2^n)
   Algorithms with exponential time complexity (O(2^n))
   have running times that grow rapidly with any increase in input size. For an
   input of size 2, an exponential time algorithm will take 2^2 = 4 time. With an
   input of size 10, the same algorithm will take 2^10 = 1024 time, and with an
   input of size 100, it will take 2^100 = 1.26765060022823 \* 1030 time. Yikes!
   The following countTriangle is meant to count the number of points in a
   triangle that looks like this:
