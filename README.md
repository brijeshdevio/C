# C Programming Language - Learning Repository

A comprehensive collection of C programming examples, exercises, and projects designed to help learn and master the fundamentals of C programming language.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Build and Run](#build-and-run)
- [Topics Covered](#topics-covered)
- [Practice Programs](#practice-programs)
- [Projects](#projects)
- [Contributing](#contributing)
- [Resources](#resources)

## 🎯 Overview

This repository contains a systematic approach to learning C programming, from basic concepts to advanced topics. Each directory focuses on specific concepts with well-documented examples and practical exercises.

## ✨ Features

- **Comprehensive Coverage**: From basics to advanced topics
- **Hands-on Examples**: Practical code examples for each concept
- **Well Documented**: Detailed explanations and comments
- **Progressive Learning**: Structured from beginner to intermediate level
- **Complete Projects**: Real-world applications like calculator
- **Best Practices**: Follows C programming conventions

## 📁 Repository Structure

```
c-programming/
├── Getting started with C Language/   # Basic introduction
├── Notes/                           # Theoretical concepts
├── operators/                       # All C operators
├── conditional_statements/          # if, else, switch statements
├── loops/                          # for, while, do-while loops
├── functions/                      # Function concepts and examples
├── arrays/                         # Array operations and matrix
├── string/                         # String manipulation
├── pointer/                        # Pointer concepts and usage
├── structure/                      # Structures and unions
├── storage_classes/                # auto, static, extern, register
├── Boolean/                        # Boolean operations
├── pattern/                        # Pattern printing programs
├── file handling/                  # File I/O operations
├── calculator project/             # Complete calculator application
├── Precedence_and_Associativity_rules/ # Operator precedence
├── Program/                        # Practice program list
└── Practice Program/               # Additional practice exercises
```

## 🚀 Getting Started

### Prerequisites

- **C Compiler**: GCC, Clang, or any standard C compiler
- **Text Editor/IDE**: Any text editor or C IDE
- **Operating System**: Linux, macOS, or Windows

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd c-programming
   ```

2. Verify your C compiler installation:
   ```bash
   gcc --version
   ```

## 🔨 Build and Run

### Compiling Individual Programs

For most single-file programs:
```bash
gcc filename.c -o output
./output
```

**Example:**
```bash
gcc hello_world.c -o hello_world
./hello_world
```

### Compiling Projects with Multiple Files

For projects like the calculator:
```bash
cd "calculator project"
gcc -c calculator.c
gcc main.c calculator.o -o calculator
./calculator
```

### General Build Commands

```bash
# Compile with debugging information
gcc -g -Wall filename.c -o output

# Compile with optimizations
gcc -O2 filename.c -o output

# Compile with all warnings
gcc -Wall -Wextra filename.c -o output
```

## 📚 Topics Covered

### Basic Concepts
- **Hello World Program**: Introduction to C syntax
- **Data Types**: int, float, double, char, etc.
- **Variables and Constants**: Declaration and initialization
- **Input/Output**: printf(), scanf(), getchar(), putchar()

### Control Structures
- **Conditional Statements**: if, if-else, nested if, switch
- **Loops**: for, while, do-while
- **Jump Statements**: break, continue, goto

### Functions
- **Function Definition**: Creating and calling functions
- **Parameter Passing**: Call by value and call by reference
- **Recursion**: Recursive function examples
- **Mathematical Functions**: Custom math operations

### Data Structures
- **Arrays**: 1D, 2D, and 3D arrays
- **Strings**: String manipulation and functions
- **Structures**: Custom data types
- **Unions**: Memory-efficient data structures

### Advanced Topics
- **Pointers**: Pointer arithmetic and applications
- **Dynamic Memory**: malloc(), free(), calloc()
- **File Handling**: File I/O operations
- **Storage Classes**: auto, static, extern, register
- **Preprocessor Directives**: #include, #define, #ifdef

### Operators
- **Arithmetic Operators**: +, -, *, /, %
- **Relational Operators**: ==, !=, <, >, <=, >=
- **Logical Operators**: &&, ||, !
- **Bitwise Operators**: &, |, ^, ~, <<, >>
- **Assignment Operators**: =, +=, -=, *=, /=, %=
- **Special Operators**: sizeof, ?, :, &, *

## 🎯 Practice Programs

The repository includes practice programs for:

1. Fibonacci series generation
2. Arithmetic operations using switch statement
3. Vowel or consonant detection
4. Star pattern printing
5. Sum of two numbers using functions
6. Even/odd number detection
7. Finding largest among numbers
8. Array input and display
9. Array element addition
10. Matrix operations and transpose
11. Number swapping using pointers
12. Call by value vs call by reference
13. Structure demonstrations
14. Union implementations

## 🛠️ Projects

### Calculator Project
A complete calculator application demonstrating:
- **Modular Programming**: Separate header and source files
- **Function Organization**: Clean code structure
- **User Interaction**: Interactive command-line interface
- **Error Handling**: Input validation

**Features:**
- Addition, subtraction, multiplication, division
- Continuous operation mode
- User-friendly interface

**Build and Run:**
```bash
cd "calculator project"
gcc -c calculator.c
gcc main.c calculator.o -o calculator
./calculator
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/new-concept`)
3. **Add** your programs with proper documentation
4. **Commit** your changes (`git commit -am 'Add new concept'`)
5. **Push** to the branch (`git push origin feature/new-concept`)
6. **Create** a Pull Request

### Guidelines
- Follow consistent coding style
- Add comments explaining complex logic
- Include example usage in comments
- Test your code before submitting
- Update documentation if needed

## 📖 Resources

### Learning Materials
- **Notes Directory**: Comprehensive C programming concepts
- **README files**: Topic-specific explanations in subdirectories
- **Code Comments**: Detailed explanations within source files

### Compilation Tips
- Use `-Wall` flag for all warnings
- Use `-g` flag for debugging information
- Use `-O2` flag for optimized builds
- Always check for memory leaks with tools like Valgrind

### Best Practices
- Follow consistent naming conventions
- Use meaningful variable names
- Comment your code appropriately
- Handle edge cases and errors
- Free allocated memory properly

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you have questions or need help:
- Check the `Notes/` directory for theoretical concepts
- Look at similar examples in the codebase
- Review the README files in specific topic directories
- Create an issue for bugs or feature requests

---

**Happy Coding!** 🚀

*This repository is designed to be a complete learning resource for C programming. Start with the basics and gradually progress through more advanced topics. Each program is designed to reinforce specific concepts and build upon previous knowledge.*
