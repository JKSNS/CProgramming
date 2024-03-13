### Introduction to C

#### History of C
C was developed in the early 1970s by Dennis Ritchie at Bell Labs. It was designed for system programming and building operating systems. Understanding its history helps appreciate its design philosophy focused on efficiency, expressiveness, and programming flexibility.

**Mini-Project:** Research and write a short essay on the evolution of programming languages leading up to C, including its influence on later languages like C++, C#, and Java.

#### Structure of a C Program
A typical C program consists of functions, variables, statements, and comments. The `main()` function is the entry point of a C program.

**Example:**
```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

#### Compiling and Executing C Programs
- **Compiling:** Transforming C code into executable code using a compiler (e.g., GCC).
- **Executing:** Running the compiled program.

**Steps:**
1. Save your program as `filename.c`.
2. Open a terminal or command prompt.
3. Compile the program: `gcc filename.c -o filename`.
4. Execute the program: `./filename`.

#### Basic Syntax
C syntax involves rules for writing statements, defining variables, and structuring the code.

**Example:**
```c
// Declaring a variable
int number = 10;

// Conditional statement
if (number > 5) {
    printf("Number is greater than 5.\n");
}
```

**Exercise:** Write a program that declares two variables, compares them, and prints which one is larger.

#### Data Types and Variables
C supports several data types, including `int`, `float`, `char`, and more. Variables are instances of data types.

**Example:**
```c
int age = 30;
float weight = 150.5;
char grade = 'A';
```

**Exercise:** Declare variables of different data types and print their values using `printf`.

#### Constants and Literals
Constants are fixed values used in C that cannot be altered by the program.

**Example:**
```c
const int MAX_AGE = 100;
printf("The maximum age is %d.\n", MAX_AGE);
```

**Exercise:** Define a constant for the maximum score and print it.

#### Storage Classes
Storage classes define the scope, visibility, and lifetime of variables or functions. The four storage classes in C are `auto`, `register`, `static`, and `extern`.

**Example:**
```c
static int count = 10; // This variable retains its value between function calls
```

**Exercise:** Create a function that uses a static variable to count how many times the function has been called.

### Mini-Project: Simple Calculator
Create a simple calculator that can perform basic arithmetic operations (addition, subtraction, multiplication, and division). The user should enter two numbers and the operation to perform.

**Requirements:**
1. Use `printf` and `scanf` for input and output.
2. Implement each operation as a separate function.
3. Ensure your program can handle division by zero gracefully.
