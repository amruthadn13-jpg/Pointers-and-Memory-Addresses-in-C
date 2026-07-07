# Pointers and Memory Addresses in C

## Overview

This project demonstrates the basics of **pointers in C**. A pointer is a variable that stores the memory address of another variable.

The program creates an integer variable, stores its memory address in a pointer, and prints both the value and the memory address.

---

## Concepts Covered

- Variables
- Pointers
- Memory addresses
- Address-of operator (`&`)
- Pointer declaration
- Formatted output using `printf()`

---

## Project Description

The program performs the following steps:

1. Creates an integer variable named `myAge`.
2. Creates a pointer `ptr` that stores the address of `myAge`.
3. Prints the value stored in `myAge`.
4. Prints the memory address of `myAge`.
5. Prints the same memory address using the pointer.

---

## Variable Declaration

```c
int myAge = 43;
```

This creates an integer variable and stores the value **43**.

---

## Pointer Declaration

```c
int *ptr = &myAge;
```

The pointer `ptr` stores the memory address of `myAge`.

---

## Address Operator

```c
&myAge
```

The `&` operator returns the memory address of a variable.

---

## Sample Output

```text
43
0x7ffe5367e044
0x7ffe5367e044
```

**Note:** The memory address will be different every time the program runs.

---

## Learning Outcomes

- Understanding pointers in C
- Using the address-of (`&`) operator
- Storing memory addresses in pointer variables
- Printing memory addresses using `%p`
- Understanding the relationship between variables and pointers

---

## Real-World Applications

- Dynamic Memory Allocation
- Arrays and Strings
- Linked Lists
- Trees and Graphs
- Embedded Systems
- Operating Systems

---

## Time Complexity

```text
O(1)
```

The program performs a fixed number of operations.

---

## Space Complexity

```text
O(1)
```

Only one integer variable and one pointer variable are used.

---

## Key Takeaway

Pointers store the memory addresses of variables, enabling efficient memory management and forming the foundation of advanced C programming concepts such as dynamic memory allocation and data structures.

---

## Author

**Amrutha D N**
