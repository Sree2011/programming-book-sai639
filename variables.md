---
layout: default
title: Variables
---

# Variables

## Definition

A variable is a symbolic name associated with a value and whose associated value may change.

## Purpose
Variables are used to store data that can be referenced and manipulated throughout a program or calculation.

## Characteristics:

### Name: 
Each variable has a unique identifier or name.
### Value: 
The data or information stored in the variable.
### Type: 
The kind of data a variable can hold (e.g., number, text, etc.).
### Usage: 
Variables allow for the storage and retrieval of data, making it easier to perform operations, calculations, and manage information dynamically.


Think of a variable as a labeled container where you can store different items (values) and change them as needed. This flexibility is crucial for creating dynamic and efficient programs or solving mathematical problems.


## Creating variables

> For information on datatypes, refer to [Datatypes](./datatypes.md)

### C programming:

**Syntax:**

DATATYPE variable_name = value;

**Example:**
```c
// variables.c
#include <stdio.h>
void main(){
    int a = 10;
    char b = 'a';
    float c = 21.87;
}
```

### Java

**Syntax:**

DATATYPE variable_name = value;

**Example:**
```java
// variables.java
public class variables{
    public static void main(String args[]){
        int a = 10;
        char b = 'a';
        float c = 21.87;
    }
}
```

### Python

**Syntax:**

variable_name = value

**Example:**
```python
# variables.py
a = 10
b = 'a'
c = 21.87
```