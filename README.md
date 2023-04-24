# Bitwise-Operations
### BITWISE OPERATOR:
  They operate on operands in a bitwise manner, meaning that they perform the operation on each corresponding bit of the operands

•	Bitwise AND operator (&): performs a logical AND operation on each corresponding bit of two operands.

•	Bitwise OR operator (|): performs a logical OR operation on each corresponding bit of two operands.

•	Bitwise XOR operator (^): performs a logical XOR (exclusive OR) operation on each corresponding bit of two operands.

•	Bitwise complement operator (~): inverts each bit of a single operand, i.e., it returns the one's complement of the operand.

•	Left shift operator (<<): shifts the bits of the left operand to the left by a number of positions specified by the right operand.

•	Right shift operator (>>): shifts the bits of the left operand to the right by a number of positions specified by the right operand.

![image](https://user-images.githubusercontent.com/91966097/234093533-cac4769a-5c84-47e1-9739-c0939a8aae71.png)

Here is the example,

 int a = 5;  // 0000 0101
 
 int b = 3;  // 0000 0011
 
 int c = a & b;  // 0000 0001 // AND OPERATOR 
 
 int s= a | b;  // 0000 0111 // OR OPERATOR 
 
 int y = a ^ b;  // 0000 0110 // XOR OPERATOR
 
 int b = ~a;  // 1111 1010  // NOT OPERATOR 

LEFT SHIFT OPERATOR -The left shift operator is represented by the symbol "<<" and is used to shift the bits of a value to the left by a specified number of positions.

The general syntax of the left shift operator is:

value << n

where "value" is the value to be shifted and "n" is the number of positions to shift the bits. 

int a = 5;  // 0000 0101

int b = a << 1;  // 0000 1010 
 
 RIGHT SHIFT OPERATOR -The right shift operator in C is represented by the symbol ">>" and is used to shift the bits of a value to the right by a specified number of positions.

The general syntax of the right shift operator is:

value >> n

where "value" is the value to be shifted and "n" is the number of positions to shift the bits. 

int a = 5;  // 0000 0101

int b = a >> 1;  // 0000 0010








