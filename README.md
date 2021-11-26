# ProgrammingAxolotys_CP4

This project encapsulates the directory structure required for the final project in CS322. The goal of this project was to use ANTLR and ASM to create a parser for the language 'KnightCode'. We used ASM and a listener to translate a parse tree into Java bytecode. This allows us to compile 'KnightCode' to the JVM. 

In order to operate the compiler, you must run three commands in order to prepare the compiler for use. These three commands are: "ant build-grammar", "ant compile-grammar", and "ant compile". Once these steps have been completed the user must run the command "java compiler/kcc tests/(Program name here) output/(Program name here)" if the user is in the base directory to run the program.

Project Members:

Justin Mattix

David Jones

Taden Duerod
