# Pseudocode Converter

A tool that converts pseudocode provided by the user into the corresponding C++ code.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
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
    git clone https://github.com/yourusername/pseudocode-converter.git
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
4. After successfully execution of project_demo.cpp. Your pseudocode(pseudo.txt) will convert into corresponding C++ code (output1.cpp).

## Examples

### Example: Find Perimeter Of Circle using Radius

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
