# Pseudocode Converter

A tool that converts pseudocode provided by the user into the corresponding C++ code.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contact](#contact)

## Introduction

The Pseudocode Converter is designed to help users convert pseudocode into C++ code easily. This tool is especially useful for students and developers who want to quickly translate their algorithm designs into executable C++ programs.

## Features

- Convert pseudocode to C++ code
- Support for basic control structures (if-else, loops, etc.)
- Easy-to-use interface

## Installation

To set up the Pseudocode Converter on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/brijesh2611999/pseudocode-converter.git
    ```


## Usage

To use the Pseudocode Converter, follow these steps:

1. Create 2 files:
    ```bash
    pseudo.txt
    ```
    ```bash
    output1.cpp
    ```
2. Enter the pseudocode in pseudo.txt.
3. Now Open project_demo.cpp file and run.
4. Your pseudocode(pseudo.txt) will convert into corresponding C++ code (output1.cpp).

## Examples:

### 1.Find Perimeter Of Circle using Radius

**Pseudocode:**
```plaintext
BEGIN
NUMBER r,perimeter 
INPUT r 
perimeter=2*3.14*r
OUTPUT perimeter
END
```
**Output:**
```cpp
#include<bits/stdc++.h>
using namespace std;
int main() {
    int r,perimeter;
    cin >> r;
    perimeter = 2 * 3.14 * r;
    cout << perimeter << endl;
    return 0;
}
```
##

### 2. Display Numbers from 1 to 100

**Pseudocode:**
```plaintext
BEGIN
NUMBER counter
FOR counter = 1 TO 100 STEP 1 DO
    OUTPUT counter
ENDFOR
END

```
**Output:**
```cpp
#include<bits/stdc++.h>
using namespace std;
int main() {
    for (int counter = 1; counter <= 100; counter++) {
        cout << counter << endl;
    }
    return 0;
}
```
##
### 3.Sum of 50 Numbers

**Pseudocode:**
```plaintext
BEGIN
NUMBER counter, sum = 0, num
FOR counter = 1 TO 50 STEP 1 DO
    OUTPUT("Enter a Number")
    INPUT num
    sum = sum + num
ENDFOR
OUTPUT sum
END
```
**Output:**
```cpp
#include<bits/stdc++.h>
using namespace std;
int main() {
    int counter, sum = 0, num;
    for (counter = 1; counter <= 50; counter++) {
        cout << "Enter a Number ";
        cin >> num;
        sum = sum + num;
    }
    cout << sum << endl;
    return 0;
}
```

## Contact

For any questions, feedback, or support regarding the Pseudocode Converter, please feel free to contact us:

- **Email**: [bv2611999@gmail.com](mailto:bv2611999@gmail.com)


