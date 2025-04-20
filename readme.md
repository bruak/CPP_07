# C++ Programming Modules

This repository contains a series of C++ modules that progressively cover various concepts in C++ programming. Each module builds upon the knowledge from previous ones, providing hands-on experience with increasingly complex aspects of the language.

## Overview

This project consists of several modules (CPP_XX) designed to introduce and explore different C++ concepts:

- **CPP_00**: Introduction to C++ basics
- **CPP_01**: Memory allocation, references, pointers, and function pointers
- **CPP_02**: Ad-hoc polymorphism, operator overloading, and orthodox canonical class form
- **CPP_03**: Inheritance and class hierarchies
- **CPP_04**: Subtype polymorphism, abstract classes, and interfaces
- **CPP_05**: Exception handling
- **CPP_06**: C++ casts (static_cast, dynamic_cast, reinterpret_cast, const_cast)
- **CPP_07**: Templates

## Module Structure

Each module contains exercises that focus on specific concepts. Each exercise is contained in its own directory with a Makefile for compilation.

### CPP_00: C++ Basics

- **ex00**: Megaphone - String manipulation and uppercase conversion
- **ex01**: PhoneBook - Introduction to classes and simple data storage

### CPP_01: Memory Management

- **ex00-01**: Zombies - Heap vs. stack memory allocation
- **ex02**: References vs. Pointers
- **ex03**: Weapon system - Different approaches to handle class associations
- **ex04**: File manipulation and string replacement
- **ex05-06**: Harl - Function pointers and complaint systems

### CPP_02: Fixed-Point Numbers

- **ex00**: Orthodox Canonical Form implementation
- **ex01**: Fixed-point number class with conversions
- **ex02**: Operator overloading for fixed-point numbers

### CPP_03: Inheritance

- **ex00**: ClapTrap - Base class implementation
- **ex01**: ScavTrap - Derived class extending ClapTrap
- **ex02**: FragTrap - Another derived class from ClapTrap

### CPP_04: Polymorphism

- **ex00**: Animal class hierarchy with runtime polymorphism
- **ex01**: Deep copying with Brain class
- **ex02**: Abstract Animal class implementation

### CPP_05: Exception Handling

- **ex00**: Bureaucrat class with custom exceptions
- **ex01**: Forms that can be signed by bureaucrats
- **ex02**: Abstract Form class with concrete implementations
- **ex03**: Intern class that creates forms (Factory pattern)

### CPP_06: C++ Casts

- **ex00**: Scalar Conversion - Converting between primitive types
- **ex01**: Serialization - Using reinterpret_cast
- **ex02**: Identifying real types with dynamic_cast and RTTI

### CPP_07: Templates

- **ex00**: Function templates
- **ex01**: Template specialization
- **ex02**: Array template implementation

## Compilation

Each exercise comes with its own Makefile supporting the following commands:
- `make`: Compile the program
- `make clean`: Remove object files
- `make fclean`: Remove object files and executable
- `make re`: Recompile the entire program

## Requirements

- C++ compiler with C++98 standard support
- Linux/macOS environment
- All code compiles with the following flags:
```
c++ -Wall -Wextra -Werror -std=c++98
```

## Key Concepts Covered

1. **Object-Oriented Programming**:
   - Classes and objects
   - Encapsulation
   - Inheritance
   - Polymorphism
   - Abstract classes and interfaces

2. **Memory Management**:
   - Stack vs. heap allocation
   - References vs. pointers
   - Deep vs. shallow copying

3. **C++ Specific Features**:
   - Operator overloading
   - Function and class templates
   - Exception handling
   - Type casting

4. **Design Patterns**:
   - Orthodox Canonical Form
   - Factory pattern

This project follows a learning path that progressively introduces more advanced C++ features while reinforcing good programming practices and design patterns.
