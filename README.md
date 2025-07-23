Program 1: helloworld.cpp
AIM:
To write a simple C++ program that displays the message “Hello, World!” on the screen.

THEORY:
The "Hello, World!" program is traditionally the very first program written by students when learning a new programming language. While it may appear trivial, it plays an important role — it introduces the fundamental structure of a C++ program and tests whether the development environment (compiler, editor, etc.) is set up correctly.

In C++, the program begins with the #include<iostream> directive, which allows the use of input-output functionalities. The function int main() serves as the entry point of the program. Inside the main() function, std::cout is used to display output to the console. The statement ends with return 0;, indicating that the program executed successfully.

This program teaches:

Basic syntax

Header inclusion

Use of main() function

Standard output using cout

Compilation and execution flow

CONCLUSION:
The program was successfully compiled and executed. The output “Hello, World!” was displayed on the screen, confirming that the C++ environment was set up correctly. Through this exercise, we understood the basic structure of a C++ program and familiarised ourselves with standard output commands. This simple exercise lays the groundwork for writing more complex programs in the future.

Program: calculator.cpp
AIM:
To write a C++ program that takes two numbers from the user and performs addition, subtraction, multiplication, and division.

THEORY:
This program is a basic arithmetic calculator implemented in C++. Instead of using menus or selection logic like switch-case, it directly computes and displays the results of all four operations — addition, subtraction, multiplication, and division — on two user-provided numbers.

The program begins by taking two floating-point numbers as input using cin. It then performs the operations sequentially and displays the results using cout. A conditional check is used before performing division to ensure the second number is not zero, preventing a runtime error due to division by zero.

Key concepts used:

Input/output in C++ (cin/cout)

Arithmetic operators: +, -, *, /

Conditional logic using if-else

Floating-point precision for accurate results

This type of calculator is foundational in understanding how data flows through a program and how basic decision-making structures work.

CONCLUSION:
The program was successfully executed and produced correct results for all four arithmetic operations. It handled division by zero gracefully using conditional checks. This exercise reinforced the use of input/output, arithmetic operators, and if-else statements in C++ and helped build logical thinking for future interactive programs.
