# nth-number
Yes, now we have the formula for the sequence.

Given the initial terms:
𝑛1=1
n2=2
n3=3
n4=4

For 𝑛≥5
n≥5, the formula for the 𝑛
n-th term is:
n(k)=n(k−1)+n(k−2)+n(k−3)+n(k−4)
 
This means each term from the 5th onward is the sum of the previous four terms. For example:

n5=n1+n2+n3+n4=10
𝑛6=𝑛2+𝑛3+𝑛4+𝑛5=19

You can now use this recurrence relation to calculate any term in the sequence!

How to run:
Java:
Compile: javac Sequence.java
Run: java Sequence
C:
Compile: gcc -o sequence sequence.c
Run: ./sequence
