# C-Day-70-Count-Divisible-by-3-or-5
# C Day 70 - Count Numbers Divisible by 3 or 5

## Description

This program takes multiple numbers from the user and counts how many numbers are divisible by either 3 or 5.

## Example

```text
Enter how many numbers: 6
Enter number 1: 10
Enter number 2: 12
Enter number 3: 7
Enter number 4: 15
Enter number 5: 20
Enter number 6: 8

Numbers divisible by 3 or 5 = 4
```

## Concepts Used

* `for` loop
* `if` statement
* Modulus operator `%`
* Logical OR operator `||`
* `count++`
* `scanf()`
* Variables

## How It Works

1. The user enters how many numbers they want to check.
2. The program takes each number using a `for` loop.
3. `%` checks whether the number is divisible by 3 or 5.
4. The `||` operator means at least one condition must be true.
5. If the condition is true, `count` is increased by 1.
6. Finally, the program displays the total count.

## Important Condition

```c
if (number % 3 == 0 || number % 5 == 0)
```

This means the number must be divisible by **3 or 5**.

## File Name

`count_divisible_by_3_or_5.c`

## Goal

The goal of this program is to practice loops, conditions, modulus, logical OR, and counting numbers based on a condition.
