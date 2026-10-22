# Sum of Digits Calculator

## About
A simple beginner-friendly Python program that calculates the sum of the digits of a positive integer entered by the user.

## How It Works
1. The program asks the user to enter a number.
2. It extracts the last digit using the modulo operator (`%`).
3. It adds that digit to the running total.
4. It removes the last digit using integer division (`//`).
5. It repeats until the number becomes zero and displays the sum.

## Example

```text
Enter a number: 5832
Sum of digits: 18
```

## How to Run
1. Make sure Python is installed.
2. Open a terminal in the project folder.
3. Run:

```bash
python sum_of_digits.py
```

## Technologies Used
- Python

## What I Learned
- Variables and user input
- `while` loops
- Modulo (`%`) and integer division (`//`)
- Basic arithmetic and output

---
## Python concepts used
1. Variables

Variables store data that our program uses.

Example: number, total, and digit.




2. User input — input()

Takes a value entered by the user.

Example: input("Enter a number: ")




3. Type conversion — int()

Converts the input text into an integer so we can perform arithmetic.

Example: int(input(...))




4. Assignment operator — =

Assigns a value to a variable.

Example: total = 0




5. While loop

Repeats a block of code while a condition is true.

Example: while number > 0:




6. Modulus operator — %

Returns the remainder after division. With a positive integer, % 10 extracts its last digit.

Example: 5832 % 10 = 2




7. Floor division — //

Divides and rounds down to the nearest integer. For positive integers, // 10 removes the last digit.

Example: 5832 // 10 = 583




8. Addition operator — +

Adds each extracted digit to the running sum.

Example: total = total + digit




9. Comparison operator — >

Checks whether one value is greater than another. It returns a Boolean result: True or False.

Example: number > 0




10. Output — print()

Displays the result on the screen.

Example: print("Sum of digits:", total)


**Author:** Viraj Sawant

*My first Python mini-project.*
