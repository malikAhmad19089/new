# Use Case: Calculate Factorial of a Number

## Use Case ID:
UC001

## Title:
Calculate Factorial of a Number

## Actor(s):
- User (inputs a number)
- System (calculates the factorial)

## Preconditions:
- The user must input a valid integer (positive integer or zero).
- The system must be running and able to perform calculations.

## Basic Flow:
1. The user is prompted to enter a positive integer or zero.
2. The user enters the number (e.g., `n`).
3. The system checks if the entered value is a valid positive integer or zero.
4. If the input is valid, the system calculates the factorial of the number `n`:
   - The factorial of a number `n` (denoted as `n!`) is the product of all positive integers less than or equal to `n`. The formula is:  
     \[
     n! = n \times (n-1) \times (n-2) \times \dots \times 1
     \]
5. The system displays the result to the user.
6. If the input is invalid, the system prompts the user to enter a valid number.

## Alternate Flow:
- If the user inputs a negative number or an invalid character (e.g., letter), the system will ask the user to input a valid positive integer or zero.
- If the input number is `0`, the system will return `1` as `0! = 1`.

## Postconditions:
- The system has calculated and displayed the factorial of the entered number.
- The system is ready to calculate the factorial for a new number.

## Expected Results:
- For input `5`, the expected output would be `120` (i.e., `5! = 5 × 4 × 3 × 2 × 1`).
- For input `0`, the expected output would be `1` (i.e., `0! = 1`).
- For an invalid input (e.g., negative number or text), the system will prompt the user to enter a valid input.
