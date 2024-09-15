# Arrays in Data Structures and Algorithms

## Overview
An **array** is a collection of elements, each identified by an index or key. Arrays are one of the simplest and most widely used data structures in programming. They are often used to store multiple values in a single variable.

Arrays can be used to store a list of elements of the same type, such as integers, strings, or objects. Arrays in most programming languages are indexed from zero, meaning the first element is accessed by `arr[0]`, the second by `arr[1]`, and so on.

## Characteristics
- **Fixed size**: Once declared, the size of an array cannot be changed. (This limitation can be bypassed by using dynamic arrays in some languages, such as Python's list or Java's `ArrayList`).
- **Homogeneous elements**: All elements in an array must be of the same data type.
- **Random access**: Any element in an array can be accessed directly using its index in constant time `O(1)`.

## Syntax
Here is how you typically declare and initialize an array in a few common programming languages:

### C++
int arr[5] = {1, 2, 3, 4, 5};


### Python
arr = [1, 2, 3, 4, 5]


### Java

int[] arr = {1, 2, 3, 4, 5};
