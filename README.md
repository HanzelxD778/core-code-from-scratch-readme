# Week challenges (Tuesday)

## 1. Interpreted And Compiled Programming Languages

### Compiled Languages

Compiled languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages, because the langugage have been already translate to code machine, so the machine just execute the code and don´t need to be checking for error, or translating from human to code to code machine in real time. They also give the developer more control over hardware aspects, like memory management and CPU usage.

Every time you want to make a change in your app or program if your using a compiled language you need to rebuild the program by doing compile and then you will see your changes in the program, if you make changes to the code but not compile the code, the program will be the same like you never made a change, if your code have an error the code will not compile, so you can´t compile until the code the code has no errors like syntaxis error

Examples of pure compiled languages are C, C++, Erlang, Haskell, Rust, and Go.

### Interpreted Languages

Interpreters run through a program line by line and execute each command. So every time you run the program, the program will be reading line by line and interprating the code, If the code has an error, the code will run in the same way, only the sections of code where the error is found will not be executed in the program, only the parts in which the code does not present any problem

Interpreted languages were once significantly slower than compiled languages. But, with the development of just-in-time compilation, that gap is shrinking.

Examples of common interpreted languages are PHP, Ruby, Python, and JavaScript.

## 2. Is Java compiled or interpreted, or both?

Java implementations typically use a two-step compilation process, a java program is first compiled into bytecode which JRE (Java Runtime Environment) can understand. ByteCode is then interpreted by the JVM (Java Virtual Machine) making it as interpreted language.

## 3. Pseudocode currency converter

### Pseudocode currency converter

#### Description

You have been selected to develop the algorithm that will be used to convert dollars (USD) to bitcoin (BTC), for this the first thing you must do is deliver a pseudocode with the algorithm to be developed, in this way you can explain in a better way to the team what will be the required operation. The main idea is to have a website where the user will be asked to enter the amount to convert.

START br
bitInDol <-- 0.000022
amountDol <-- 0
value <-- 0
PRINT enter the amount of dollars
amountDol <-- GET
value <-- amountDol * bitInDol
PRINT value
END
