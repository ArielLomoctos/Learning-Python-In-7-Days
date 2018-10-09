# Learning-Python-In-7-Days
Documentation of Python fundamentals -- Python is a very good programming language however not understanding the basic might be a daunting learning phase for anyone who loves to learn the language.

`Getting Started` `Variables and Operators` `Strings` `List` `Dictionary` `Control Statements and loops` `Function and Scope of Variable` `Modules and Packages` `File Handling and Exceptions` `Collections` `Class and Objects`

### `DAY 01: GETTING STARTED WITH PYTHON`

## Requirement
- Install <b>Anaconda Distribution</b>
  - Read [`Anaconda Documentation`](https://enterprise-docs.anaconda.com/en/latest/)
  - After Installation, Find path of Python.exe in the distributed package of Anaconda
  - If you can't find the Python.exe path, try to: (1) Windows> Jupyter> Open File Location (2) Jupyter Notebook> Open File Location. Python exe. should be highlighted from Anaconda Package Folder.
- Install IDE (Integrated Development Environment)
  - You just need to select any of the 2 most favored IDE:
    - Install [`Sublime 3`](https://www.sublimetext.com/3) or [`Visual Studio Code`](https://code.visualstudio.com/docs)
- CMD (Command Prompt)
  - How to run .py file in command prompt
```
  C:\Users\User\AppData\Local\Continuum\anaconda3\python.exe C:\Users\User\Desktop\helloworld.py
```
## Why Learn Python
- Python program runs on any platform (Windows, Mac OSx, Linux) this really gives you an advantage of learning a language and implementing it on any known platforms.
- Python has inbuilt large libray with prebuild and portable functionality also known as [`Python Standard Library`](https://docs.python.org/3/library/), easy to learn [`Python Language Reference`](https://docs.python.org/3/reference/index.html#reference-index), and [`Python 3 Documenation`](https://docs.python.org/3/)
- Python can be both dynamically and strongly typed (means it is a type of variable that is interpreted at runtime which mean, in Python, there's no need to define the type of the variable.

# Getting Started
- `Comments` - There are two types of comments -- one is single-line comment (#) and multiline comment (""").
- `Basic Syntax` Use print("Hello World") to print a string
- `Escape Sequence` - The Escape Sequence is used to (t) insert tab, (n) new line, (b) backspace and other special character code. They give you greater control and flexibility to format your statement and code.
- `Concatenation` - Use print("Hello" + "World")
- `Formatted Output` - Use %d (integer), %f (float), %s (string)
- `Indentation` - The most unique characteristics of Python unlike other programming language is indentation. Indentation not only makes code readability but also distinguish each block of code from the other. If the indentation is not strictly implemented then code execution will throw an error. Read [`Spaces vs Tab`](https://docs.python.org/2.0/ref/indentation.html) Python indentation rules.

# Variable Type
- Learn assignment statements, arithmentic, comparison, assignment, bitwise, logical, membership, identity operators.
- What is a `VARIABLE`: A variable refers to the value that stored in the memory. When you create a variable, the interpreter will reserve some space in the memory to store values. Depending on the data type of the variable, the interpreter allocated memory and makes a decision to store a particular data type in the reserved memory.
- Python variable usually  `dynamically typed` (type of variable is interpreted during runtime and you need not specifically provide a type to the variable name, unlike what the other programming language required.
- Rules `Reserve Keyword` `Variable can start with _ $ or a letter` `Variable can be upper or lower case` `Variable should not start with numbers` `Whitespace are not allowed` `Assign values to variable using =`
- Python `Data Types` `Numbers (Integers, Long Integers, Floating, Complex, Boolean),` `Strings (Text),` `Tuples,` `List,` `Dictionary`
- `Single Assignment` MyVar = "Hello World" `Values can be any of data types`
- `Multiple Assignment` a=b=c=1 `(a = b, b=c, c=1, therefore a, b, and c are all equal to 1)`

# Operators
- <b>Arithmetic expression:</b> ` ** exponent,` `* multiplication,` `/ Division,` `% Modulus ret. remainder,` `- Subtraction,` `+ Addition`
- <b>Comparisson operators:</b> these operators return True or False, `= Equality,` `< Less than,` `> Greater than,` `<= Less Than or Equal to,` `>= Greater Than or Equal to,` `!= Not Equal To,` `<> Left and Right are not equal expression,`
- Variants of assignment operator which often used in combination with arithmetic operators.

| Operator| Description |
| --- | --- |
| = | x = y, y is assigned to x |
| += | x += y, x = x+y |
| -= | x -= y, x = x-y |
| x= | x * = y, x = x * y |
| ** = | x ** y, x = x ** y|

- <b>Bitwise Operators:</b> signed binary numbers ! & ~ << >>
- <b>Logical Operators:</b> And, Or, Not
- <b>Membership Operators:</b> Python has the membership operator to test the membership in a sequence, such as string, list, tuple, and others. `in` found in the sequence `not in` not found in the sequence
- <b>Identity Operators:</b> If variable or object have the same memory address during lifetime. `is` ret. True point to the same object `is not` ret. False point in the same object

### `DAY 02: STRINGS`
