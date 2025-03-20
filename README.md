# InfinityCalc

## 📚 Overview
Welcome to **MegaNumEngine**, your go-to solution for handling large integers with ease! This project allows you to perform various arithmetic operations on big integers that exceed standard data types.

## 🛠️ Getting Started
To get started, open this code in your favorite editor and dive into the main function to explore its capabilities!

### 📝 Declaration
You can declare a **BigInt** variable just like any other variable:

```cpp
G_BigInt x, y, z;
```

### 🚀 Initialization
You can initialize **G_BigInt** in two ways:
1. **Using Constructor**:
   ```cpp
   G_BigInt x("23243");
   ```
2. **Using String**:
   ```cpp
   string str = "3435453543";
   G_BigInt x = str;
   ```

**Note**: You cannot initialize using:
```cpp
G_BigInt x = "2324"; // Not allowed
G_BigInt x = 23434235435345454; // Not allowed
```

## 🔍 Input and Output
- **Input**: Use `cin >> variable_name;`
- **Output**: Print using `cout << variable_name;`

## ➕ Arithmetic Operations
You can perform the following arithmetic operations just like with standard integers:
- **Addition**: `+`
- **Subtraction**: `-`
- **Multiplication**: `*`
- **Division**: `/`
- **Remainder**: `%`

Make sure both operands are of type **G_BigInt**.

## 🔗 Relational Operators
You can compare two **G_BigInt** variables using:
- `<`, `<=`, `>`, `>=`, `==`, `!=`

## ⏩ Increment and Decrement
Use the same syntax as integers:
```cpp
x++; // Increment
++x; // Pre-increment
x--; // Decrement
--x; // Pre-decrement
```

## ⚖️ Assignment Operators
Perform assignment operations seamlessly:
```cpp
x += y; // Add and assign
x -= y; // Subtract and assign
x *= y; // Multiply and assign
x /= y; // Divide and assign
x %= y; // Modulus and assign
```

## 🔄 Sign Change
You can change the sign of a **G_BigInt** variable just like you would with integers:
```cpp
x = -x; // Changes x to -x
```

---

