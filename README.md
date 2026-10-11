# Python For Loops – Beginner Practice

## Description
This project demonstrates how to use `for` loops and the `range()` function in Python to repeat instructions automatically.

The program contains two examples:
1. Printing a message 101 times.
2. Printing numbers from 0 to 100.

## Python Code

```python
# Example 1: Print a message 101 times
for number in range(0, 101):
    print("my name is fred")

# Example 2: Print numbers from 0 to 100
for number in range(0, 101):
    print(number)
```

## Code Explanation

**Example 1: Repeating a message**

- `for number in range(0, 101):` creates a loop that runs 101 times.
- `print("my name is fred")` prints the same message during every loop.

**Example 2: Printing numbers**

- `range(0, 101)` generates numbers starting at 0 and stopping at 100.
- `number` stores the current number during each loop.
- `print(number)` displays each number.

## Expected Output

**Example 1:**
```text
my name is fred
my name is fred
my name is fred
... (repeated 101 times)
```

**Example 2:**
```text
0
1
2
3
...
98
99
100
```

## Key Concepts Learned

- **For loop:** Repeats a block of code.
- **range():** Generates a sequence of numbers.
- **Indentation:** Tells Python which instructions belong inside the loop.
- **print():** Displays information on the screen.

## Technologies Used
- Python 3

## Learning Objective
Understand how to automate repetitive tasks using Python `for` loops instead of writing the same instructions multiple times.
