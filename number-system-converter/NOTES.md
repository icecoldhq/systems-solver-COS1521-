# Enum

I don't know much about what enum is. This is what I understand about it so far:

## What is an Enum:
- Enum stands for enumeration. It's a way that you can define a custom type that holds a set of named constant values in C++
- Think of Enum like a list of lables, each representing a specifc fixed value.
- This makes my code easier to read and less error-prone because I'm using meaningful anmes instead of raw numbers.

## Why use an Enum for Number Systems?
- In my number converter, I'll be working with bases like 2, 8, 10, and 16. Instead of using these numbers everywhere and risking making mistakes or magic numbers, I'll define an enum to represent these bases clearly and give them meaningful names.

## Test cases

Here's my C++ code that I used to test my Enum function:

#include <iostream>
using namespace std;

// Defining enum for the number systems

enum NumberSystem {
    BINARY = 2,
    OCTAL = 8,
    DECIMAL = 10,
    HEXADECIMAL = 16
};

int main()
{
    cout << "Testing NumberSytem enum values:\n";

    cout << "BINARY: " << BINARY << endl;
    cout << "OCTAL: " << OCTAL << endl;
    cout << "DECIMAL: " << DECIMAL << endl;
    cout << "HEXADEMICAL" << HEXADECIMAL << endl;

    return 0;
}

## Notes:

I haven't programmed since November last year, and I only used C++ then. I'm using AI (ChatGPT) to help me with writing code and learning too. 

I do wonder if Enum is just another way of representing a function in C++?
