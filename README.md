# C-Duplicate-Element-Finder
# Find Duplicate Elements in an Array

## Explanation

This C program identifies duplicate elements present in an array.

The program compares each element with the elements that come after it. If two elements are equal, the value is considered a duplicate.

## Problem Statement

Write a C program to find duplicate elements in an array.

## Features

- Accepts array elements from the user
- Identifies duplicate values
- Uses nested loops
- Handles arrays with no duplicates
- Displays duplicate elements

## How It Works

1. Read the number of elements.
2. Read the array elements.
3. Select one element at a time.
4. Compare it with the elements after it.
5. If a matching element is found, display it.
6. If no duplicate exists, display an appropriate message.

## Technologies Used

- C Programming Language
- Standard Input/Output

## Data Structure Used

- Array

## Methods Used

- `main()`
- `scanf()`
- `printf()`

## Program Flow

Start
↓
Read number of elements
↓
Read array elements
↓
Compare elements using nested loops
↓
Check for duplicates
↓
Display duplicate elements
↓
End

## Sample Input

Enter the number of elements: 7
Enter 7 elements:
10 20 10 30 40 20 50

## Sample Output

Duplicate elements are:
10 20

## Time Complexity

O(n²)

## Space Complexity

O(n)

## Key Learning

- Understanding nested loops
- Comparing multiple array elements
- Finding duplicate values
- Using array indexes
- Applying conditional statements

## File Location

`find_duplicate_elements.c`

## Repository Structure

C-Duplicate-Element-Finder/
│
├── find_duplicate_elements.c
└── README.md

## Author

V.Harini
