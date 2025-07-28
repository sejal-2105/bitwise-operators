Bitwise operators in cpp

AIM:-
To study and implement bitwise operators in cpp

Tools:-
VScode and github

Theory:-
Bitwise operators perform operations on the binary representation of integers.
The AND (&), OR (|), and XOR (^) operators compare bits and return a new value based on bit-level logic.
The NOT (~) operator inverts all bits. The left shift (<<) and right shift (>>) operators shift bits to the left or right, effectively multiplying or dividing the number by powers of two.

Bit manipulation allows setting or clearing specific bits. To set a bit at position n, the expression num | (1 << n) is used. To reset a bit at position n, the expression num & (~(1 << n)) is used. These techniques are essential for low-level programming and memory-efficient operations.

Algorithm:-
Part 1: Bitwise Operations
1.Start the program.
2.Declare two integer variables a and b.
3.Prompt the user to enter values for a and b.
4.Perform and display the results of:
a & b (AND)
a | b (OR)
a ^ b (XOR)
~a and ~b (NOT)
a << 1 (left shift)
b >> 1 (right shift)

Part 2: Bit Set and Reset
1.Prompt the user to enter a number num.
2.Ask for a bit position bit_set to set.
3.Compute set = num | (1 << bit_set).
4.Display the number after setting.
5.Ask for a bit position bit_reset to reset.
6.Compute reset = num & (~(1 << bit_reset)).
7.Display the number after resetting.
8.End the program.

Conclusion:-
The experiment successfully demonstrated basic bitwise operations and bit manipulation in C++. These operations are efficient and crucial for controlling data at the binary level, particularly in embedded systems, hardware interfacing, and performance optimization.



