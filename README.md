Get Started with C, C++, and C#
1. Setup:

C/C++:

Install GCC/G++ (GNU Compiler Collection)

Windows: MinGW

Linux: sudo apt install build-essential

macOS: brew install gcc

IDE/Editor:

VSCode (with the C/C++ extension)

Code::Blocks (IDE for C/C++)

CLion (for C/C++)

C#:

Install Visual Studio (Windows) or Visual Studio Code (Cross-platform)

Download Visual Studio from Visual Studio Downloads

2. Basic Concepts:
C (Language Basics)

Variables and Data Types

int, float, char, double, bool

Example:

int age = 20;
printf("Age: %d", age);


Control Flow: if, else, for, while

Example:

for (int i = 0; i < 10; i++) {
    printf("%d ", i);
}


Functions: How to create and use functions.

Example:

int add(int a, int b) {
    return a + b;
}

C++ (Object-Oriented Concepts)

Classes and Objects

C++ supports Object-Oriented Programming (OOP) like classes, constructors, and destructors.

Example:

class Car {
private:
    string brand;
public:
    Car(string b) : brand(b) {}
    void display() {
        cout << "Brand: " << brand << endl;
    }
};
int main() {
    Car myCar("Toyota");
    myCar.display();
    return 0;
}


STL (Standard Template Library)

Learn about Vectors, Maps, Queues, etc.

Example:

#include <iostream>
#include <vector>

int main() {
    std::vector<int> numbers = {1, 2, 3, 4};
    numbers.push_back(5);
    for (int num : numbers) {
        std::cout << num << " ";
    }
}

C# (Modern Object-Oriented)

Variables, Classes, and Methods

Example:

class Person {
    public string Name { get; set; }
    public int Age { get; set; }

    public void DisplayInfo() {
        Console.WriteLine($"Name: {Name}, Age: {Age}");
    }
}


LINQ and Collections

Working with Lists and LINQ queries.

Example:

List<int> numbers = new List<int> { 1, 2, 3, 4, 5 };
var evens = numbers.Where(n => n % 2 == 0).ToList();

Beginner Exercises
C - Basic Exercises

Hello World: Print "Hello, World!" to the console.

Sum of Numbers: Write a program that sums all numbers from 1 to 100.

Even or Odd: Write a program that asks for a number and tells you if it's even or odd.

Factorial: Write a program that calculates the factorial of a number.

C++ - Object-Oriented Exercises

Class Inheritance: Create a Vehicle class and derive a Car class from it.

Bank Account: Write a program that simulates a bank account with deposit and withdrawal methods.

Array Manipulation: Create a program that stores an array of integers and sorts them using Bubble Sort or Selection Sort.

C# - Object-Oriented Exercises

Student Class: Create a Student class with properties like name, age, and grades, and display them.

Book Library: Create a program to manage a simple library where you can add, remove, and view books.

Palindrome Check: Write a method that checks if a string is a palindrome.

Resources to Learn C, C++, and C#
C Resources:

C Programming Tutorial

Book: "The C Programming Language" by Brian W. Kernighan and Dennis M. Ritchie

GeeksforGeeks C Programming

C++ Resources:

C++ Programming

Book: "C++ Primer" by Stanley B. Lippman

GeeksforGeeks C++ Tutorial

C# Resources:

C# Documentation (Microsoft)

Book: "C# 9.0 in a Nutshell" by Joseph Albahari

GeeksforGeeks C#

Example Files to Practice

C Example (basic_c.c)

#include <stdio.h>

int main() {
    int num1, num2, sum;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    sum = num1 + num2;
    printf("Sum: %d\n", sum);
    return 0;
}


C++ Example (basic_cpp.cpp)

#include <iostream>
using namespace std;

class Rectangle {
private:
    int length, width;
public:
    Rectangle(int l, int w) : length(l), width(w) {}
    int area() {
        return length * width;
    }
};

int main() {
    Rectangle rect(5, 3);
    cout << "Area: " << rect.area() << endl;
    return 0;
}


C# Example (BasicProgram.cs)

using System;

class Program {
    static void Main() {
        Console.WriteLine("Enter your name: ");
        string name = Console.ReadLine();
        Console.WriteLine($"Hello, {name}!");
    }
}

Next Steps

Once you're comfortable with the basics, try building small projects, such as:

A To-Do List app (for all three languages)

A Calculator

A Simple Game (like Tic-Tac-Toe or a number guessing game)
