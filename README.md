# InfinityCalc

## Overview
Welcome to **InfinityCalc**, a robust solution for handling arbitrary-precision integers. This library provides efficient arithmetic operations for integers that exceed standard data type limitations.

## Features
- Arbitrary-precision integer arithmetic
- Full support for standard mathematical operations
- Optimized performance with Karatsuba algorithm for multiplication
- Intuitive syntax similar to built-in types

## Getting Started
To get started, include the header file in your project and begin using the G_BigInt class.

### Declaration
Declare a G_BigInt variable like any standard variable:
```cpp
G_BigInt x, y, z;
```

### Initialization
You can initialize G_BigInt in two ways:

1. Using Constructor:
   ```cpp
   G_BigInt x("23243");
   ```

2. Using String:
   ```cpp
   string str = "3435453543";
   G_BigInt x = str;
   ```

**Note**: The following initializations are not supported:
```cpp
G_BigInt x = "2324"; // Not allowed
G_BigInt x = 23434235435345454; // Not allowed
```

## Input and Output
- **Input**: Use `cin >> variable_name;`
- **Output**: Print using `cout << variable_name;`

## Arithmetic Operations
The following arithmetic operations are supported:
- Addition: `+`
- Subtraction: `-`
- Multiplication: `*` (Uses Karatsuba algorithm for improved performance)
- Division: `/`
- Remainder: `%`

Both operands must be of type G_BigInt.

## Performance Optimization
This implementation uses the Karatsuba algorithm for multiplication, which significantly improves performance for large integers. The algorithm has a time complexity of O(n^log₂3) ≈ O(n^1.585), compared to the classical algorithm's O(n²).

## Relational Operators
Compare two G_BigInt variables using:
- `<`, `<=`, `>`, `>=`, `==`, `!=`

## Increment and Decrement
Use the same syntax as integers:
```cpp
x++; // Increment
++x; // Pre-increment
x--; // Decrement
--x; // Pre-decrement
```

## Assignment Operators
Perform assignment operations:
```cpp
x += y; // Add and assign
x -= y; // Subtract and assign
x *= y; // Multiply and assign
x /= y; // Divide and assign
x %= y; // Modulus and assign
```

## Sign Change
Change the sign of a G_BigInt variable:
```cpp
x = -x; // Changes x to -x
```

