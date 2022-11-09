We are given an arithmetic expression with brackets. Scan through the string and extract each sub‐expression.
Print the result back at the terminal.
Hints:
 Scan through the expression searching for brackets
o If you find an opening bracket, push the index into the stack
o If you find a closing bracket pop the topmost element from the stack. This is the index of the
opening bracket.
o Use the current and the popped index to extract the sub‐expression
