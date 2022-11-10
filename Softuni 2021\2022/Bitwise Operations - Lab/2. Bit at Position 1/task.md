Write a program that prints the bit at position 1 of given integer. We use the standard counting: from right to left,
starting from position 0.
You will receive one number you need to convert binary.

Hints:
1. Declare two variables (n and bitAtPosition1).
2. Read the user input from the console.
3. Find the value of the bit at position 1 (position 1 is the second bit from right to left: [7, 6, 5, 4, 3, 2, 1, 0]):
a. Shift the number n times to the right (where n is the position, in this case it is 1) by using the >>
operator. In that way the bit we want to check will be at position 0;
b. Find the bit at position 0. Use & 1 operator expression to extract the value of a bit. By using the
following formulae (bitAtPosition1 & 1) you check whether the bit at position 0 is equal to 1 or
not. If the bit is equal to 1 the result is 1 if the bit is not equal ‐ the result is 0;
c. Save the result in bitAtPosition1;
4. Print the result on the console.
