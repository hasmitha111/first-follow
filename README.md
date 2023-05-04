
## Description

This program takes a context-free grammar as input and computes the First and Follow sets for a specified non-terminal symbol. The input grammar is assumed to be in Chomsky Normal Form, where all productions have the form A → BC or A → a, where A, B, and C are non-terminal symbols and a is a terminal symbol.

## Grammar Format

The user is prompted to enter the number of productions and then the productions themselves, one per line, in the following format:

A → BC

or

A → a

where A, B, and C are non-terminal symbols and a is a terminal symbol. The user is then prompted to enter the non-terminal symbol for which the First and Follow sets are to be computed.

## Running the Code

To compile the code, you can use a C compiler such as gcc:

```
gcc parser.c -o parser
```

To run the code, simply execute the compiled binary and follow the prompts:

```
./parser
```

The program will prompt you to enter the number of productions, then the productions themselves, and then the non-terminal symbol for which the First and Follow sets are to be computed. The program will then output the First and Follow sets for the specified non-terminal symbol.



