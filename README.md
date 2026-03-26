# <img src="assets/logo.png" width="50"> Python Introduction

Python is a general purpose programming language used across all industries. It is increasingly popular due to its readability and beginner friendliness; it has overtaken Javascript as the top coding language.

## Table of Contents
- [ Python Introduction](#-python-introduction)
  - [Table of Contents](#table-of-contents)
    - [The Computer Recipe:](#the-computer-recipe)
  - [I. Strings](#i-strings)
  - [II. Indexing](#ii-indexing)
  - [III. Data Types](#iii-data-types)
    - [Numeric Data Types](#numeric-data-types)
    - [Boolean Data Types](#boolean-data-types)
  - [IV. Data Structures](#iv-data-structures)
  - [V. Loops](#v-loops)
  - [VI. Functions](#vi-functions)
  - [Glossary](#glossary)

### The Computer Recipe:
Programming is a set of instructions so that the computer can run functions.\
Algorithms are step-by-step rules to solve a problem.\
The computer has two states: On and Off. Binary code represents the two modes.\
Coding is an interatve process: Code, test, debug.

## I. Strings
A sequence of characters.
  + Can include alphanumerics and special characters. 
  + Enclose with open and close quotation marks.
  + Strings with empty values can be represented by two quotation marks. " "

**Raw Strings:** Preceeds the string literal with an r character to make the code cleaner and easier to read.

**String Manipulation & Typecasting, Built-in Methods**
  + f string: print(f"Hello World")
  + Concatenate Text: using a comma within the function. Automatically inserts a space between the two texts. 
  + Curly Brackets {}: You can concatenate specific variables and text. 
  + Upper(): converts text to all uppercase. 
  + count(): gives number of something.
  + replace(): replaces one text with another by using concatenated text in the function. 
  + len(): gives the length of requested text.
  + strip(): removes both ends of text. 
  + is Methods: returns boolean value.
  + isalnum(): every character is alphanumeric. 
  + isalpha(): every character is alphabetic. 
  + isdigit(): every character is numeric. 
  + isupper(): every character is uppercase. 
  + islower(): every character is lowercase. 

## II. Indexing
Extraction of parts of text. []
  + Colon: Extracts first character of text from left to right or right to left. 
    + Slice a string literal by putting starting index followed by colon and then the ending index. 
  + Use negative or positive integer values to distinguish order of left to right or right to left. 

## III. Data Types
### Numeric Data Types
  + Integers: Numbers 0-9, positive or negative, whole numbers only. 
  + Floating Point Numbers: Includes a decimal point. 

### Boolean Data Types 
  + True or False values
  + bool(): Built-in function that represents the true/false of any argument passed to it. 

NONE keyword: null value. \
NONETYPE: data type of NONE. 

## IV. Data Structures 
  + Primitive/Basic: 
  + Complex: 

## V. Loops
Control structures that loops back to repeat a block of codes
+ Nested Loops: Performs loops within another loop. 
+ While Loops: KEYWORD while followed by a condition. Once the condition becomes FALSE, the loop will end. 

## VI. Functions
Designed to be reusable code, performs only one task.

Types of functions:
  + Built-in functions: abs(), print(), float(), tuple(), list()
  + User defined functions \
Parts of a function:
  + Definition 
  + Function call


## Glossary
**Functions:** Identified by a close and open parentheses ()\
**Arguments:** Located within the function- what you want the output to be.\
**Variable:** something that varies or changes.\
**Assignment Operator:** Assigns a name to a _variable._ \
**CamelCase:** Starting the assignment of a variable with a lowercase letter and the second word with an uppercase letter, sometimes distringued with an underscore_. \
**Case Sensitive:** Python keywords are eclcuded from value assignment. \
**Escape Character:** Backslash character within a string literal interpreted as an escape character. Makes code cleaner and easier to read. Used to insert characters that would otherwise be illegal in a string. \
**Empty Strings:** Strings that contain empty values. \
**Raw Strings:** Preceeds the string literal with an r character to make the code cleaner and easier to read. \
**Typecasting:** Data type conversion; allows you to specify a data type to a variable or to convert a variable from one data type to another. \
**Lists:** collection of data which is _ordered_ and _mutable_. \
**Dictionaries:** 
**Operators:** Perform operations on values.
  + Operand: Variables/values performed on.
  + Expressions: Result in values. Comprised of operators and operands.
  + Assignmnet operators: Assign values to variables. 