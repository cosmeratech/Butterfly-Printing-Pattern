# Butterfly Pattern Generator

A C++ program that generates a beautiful butterfly pattern using asterisks (*).

## Description

This program creates a symmetrical butterfly pattern where:
- The upper half forms an increasing pattern
- The lower half mirrors the upper half in reverse
- The pattern is centered with spaces between the wings

## How it Works

The program uses nested loops to create two main sections:

### Upper Part (Lines 11-26)
- Creates increasing number of asterisks on each side
- Calculates spaces between wings: `2 * (rows - i)`
- Forms the top half of the butterfly

### Lower Part (Lines 29-44)
- Mirrors the upper part in reverse order
- Uses the same spacing calculation
- Completes the butterfly shape

## Usage

1. Compile the program:
```bash
g++ -o butterfly higga.cpp
```

2. Run the executable:
```bash
./butterfly
```

3. Enter the number of rows when prompted

## Example Output

```
Enter the Number of rows : 4
Butterfly Pattern of 4 rows.
*        *
**      **
***    ***
****  ****
**********
****  ****
***    ***
**      **
*        *
```

## Requirements

- C++ compiler (g++, clang++, etc.)
- Standard input/output library

## Algorithm Complexity

- **Time Complexity**: O(n²)
- **Space Complexity**: O(1)

Where n is the number of rows.
