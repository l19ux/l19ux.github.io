---
layout: post
title: Probelm based on operations on a sequence
---

[Problem 2062C](https://codeforces.com/problemset/problem/2062/C)  <details>
  
```scala
Let the reversal be called operation 1, and the difference be called
operation 2. Consider swapping two adjacent operations: 
12→21. If the sequence before the operations is [a1,a2,…,an], then
after the operations, the sequence changes from 
[an−1−an,an−2−an−1,…,a1−a2] to [an−an−1,an−1−an−2,…,a2−a1]. 
Thus, swapping adjacent 1,2 is equivalent to taking the negation of
each element of the array. 

Therefore, any operation sequence is equivalent to first performing
2 several times, and then performing 1 several times, 
and then taking the negation several times. Since 1 does not change
the sum of the sequence, the answer is the maximum absolute 
value of the sequence sum after performing a certain number of 2.
```

</details>
