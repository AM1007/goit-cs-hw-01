# Module 1. Computer architecture

## Chapter 01 - Topic 1 Introduction to computer architecture

Develop an assembler program that calculates the result of the expression 'variable_b minus variable_c plus variable_a' and stores the outcome in a specified memory address.

## Chapter 02 - Topic 2 Introduction to compilers and interpreters

1. Enhance `Lexer` Functionality

Introduce additional token types to accommodate multiplication `MUL`, division `DIV`, and parentheses, encompassing both opening `LPAREN` and closing `RPAREN` components within arithmetic expressions.
Revise the `get_next_token` method within the `Lexer` class to appropriately identify and handle these newly introduced characters.

2. Modify the `Parser`

- Incorporate a `factor` method to manage both numbers and expressions enclosed within parentheses.
- Adjust the `term` method to encompass multiplication and division operations.
- Ensure that the `expr` method is appropriately updated to accommodate the revised hierarchy of operations.

3. Update the `Interpreter`

Expand the functionality of the `visit_BinOp` method within the `Interpreter` class to include handling of multiplication and division operations.

4. Testing

Verify the accuracy of the interpreter's calculations across a range of arithmetic expressions, including those involving parentheses. For example, ensure that `(2 + 3) * 4` results in `20`.
