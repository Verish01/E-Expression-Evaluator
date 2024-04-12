# E-Expression-Evaluator Project

Overview:
Developed a comprehensive expression evaluator for the E++ language, capable of interpreting and computing the results of complex mathematical expressions involving arithmetic operations and variables. This project involves implementing components such as UnlimitedInt and UnlimitedRational classes for handling unlimited-precision integers and rational numbers, respectively.

UnlimitedInt Class: Implemented to handle integers of arbitrary size, this class supports operations such as addition, subtraction, multiplication, division, and modulus using dynamic memory allocation.

UnlimitedRational Class: Extended the UnlimitedInt capabilities to handle rational numbers represented as a pair of UnlimitedInts (numerator and denominator), ensuring operations on rational numbers maintain high precision without overflow issues.

Expression Parsing and Evaluation: Built a parser that converts E++ program statements into a parse tree structure, capturing the syntactic structure of expressions and handling variables and constants dynamically.

Symbol Table: Implemented using a Binary Search Tree (BST), the symbol table manages variable declarations and lookups efficiently, ensuring each variable is assigned only once and is declared before use, aligning with E++ language constraints.

Evaluator Module: Integrated parsing and evaluation logic to compute expression values and update the symbol table accordingly, facilitating variable resolution and expression computations based on the parse tree.
