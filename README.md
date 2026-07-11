# Infix to Postfix Converter & Expression Evaluator

A C++ console-based application that converts mathematical expressions from **Infix** notation to **Postfix (Reverse Polish Notation)** and evaluates the resulting postfix expression using the **Stack** data structure. This project demonstrates expression parsing, operator precedence, associativity, and stack-based expression evaluation.

---

##  Features

- Convert infix expressions to postfix notation
- Evaluate postfix expressions
- Support arithmetic operators:
  - Addition (`+`)
  - Subtraction (`-`)
  - Multiplication (`*`)
  - Division (`/`)
  - Modulus (`%`)
  - Exponentiation (`^`)
- Handle parentheses correctly
- Support trigonometric functions:
  - `sin()`
  - `cos()`
  - `tan()`
- Apply operator precedence and associativity rules
- Display the generated postfix expression
- Compute and display the final result
- Interactive console-based interface

---

##  Tech Stack

- **Language:** C++
- **IDE:** Microsoft Visual Studio
- **Data Structure:** Stack

---

##  Project Structure

```text
Infix-to-Postfix-Converter/
│
├── InfixToPostfixConverter.cpp
└── README.md
```

> **Note:** If your source file has a different name (such as `main.cpp` or `Source.cpp`), replace `InfixToPostfixConverter.cpp` with the actual filename.

---

##  How It Works

1. The user enters an infix mathematical expression.
2. The program converts the expression into postfix notation using a stack.
3. The generated postfix expression is displayed.
4. The postfix expression is evaluated.
5. The final result is printed on the console.

---

##  Supported Expressions

### Arithmetic

```text
(5 + 3) * 2
```

### Trigonometric

```text
sin(30)
cos(60)
tan(45)
```

### Combined Expressions

```text
5 + sin(30) * 4
(10 + cos(60)) / 2
```

---

##  Concepts Demonstrated

- Stack Data Structure
- Infix to Postfix Conversion
- Postfix Expression Evaluation
- Expression Parsing
- Operator Precedence
- Associativity Rules
- Mathematical Expression Processing
- Trigonometric Function Evaluation
- Console Application Development

---

##  Getting Started

### Clone the Repository

```bash
git clone https://github.com/SameenAli888/INFIX-TO-POSTFIX-CONVERTER.git
```

### Run the Project

1. Open the `.cpp` file in **Microsoft Visual Studio** or any C++ IDE.
2. Build or compile the project.
3. Run the program.
4. Enter an arithmetic or trigonometric expression when prompted.

---

##  Future Improvements

- Support logarithmic functions
- Support inverse trigonometric functions
- Improve input validation and error handling
- Add floating-point precision controls
- Develop a graphical user interface (GUI)
- Store expression history

---

##  Learning Outcomes

This project helped strengthen my understanding of:

- Stack implementation in C++
- Expression conversion algorithms
- Mathematical expression evaluation
- Operator precedence handling
- Console-based application development

---

