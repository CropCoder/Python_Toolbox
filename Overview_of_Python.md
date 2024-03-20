# Overview of Python

## Python Functions

- `float`: converts a string or a number to a floating point number, e.g., `float("3.14")` returns `3.14`
- `int`: converts a string or a number to an integer, e.g., `int("3.14")` returns `3`
- `in`: checks if a value is in a list, e.g., `3 in [1, 2, 3]` returns `True`
- `print`: prints a value to the console, e.g., `print("Hello, World!")` prints "Hello, World!"
- `exit`: exits the program and returns to the command line
- `append`: adds an element to the end of a list, e.g., `list.append(4)` adds `4` to the end of `list`
- `len`: returns the length of a list, e.g., `len([1, 2, 3])` returns `3`
- `return`: returns a value from a function, e.g., `return three` returns `3`
- `input`: gets input from the user, e.g., `input("Enter a number: ")` gets a number from the user
- `split`: splits a string into a list of strings, e.g., `"1 2 3".split()` returns `["1", "2", "3"]`
- `str.isdigit`: checks if a string is a number, e.g., `"123".isdigit()` returns `True`
- `str.find`: finds the index of a substring in a string, e.g., `"Hello, World!".find("World")` returns `7`
- `str.index`: finds the index of a substring in a string, e.g., `"Hello, World!".index("World")` returns `7`
- `str.upper`: converts a string to uppercase, e.g., `"hello".upper()` returns `"HELLO"`
- `str.slice`: returns a slice of a list, e.g., `list[1:3]` returns `[2, 3]`
- `str.join`: joins a list of strings with a string, e.g., `", ".join(["apple", "banana", "cherry"])` returns `"apple, banana, cherry"`
- `str.strip`: removes leading and trailing whitespace from a string, e.g., `"  Hello, World!  ".strip()` returns `"Hello, World!"`
- `str.split`: splits a string into a list of strings, e.g., `"1 2 3".split()` returns `["1", "2", "3"]`
- `str.replace`: replaces a substring with another substring in a string, e.g., `"Hello, World!".replace("World", "Python")` returns `"Hello, Python!"`

## Python Modules

- `math`: provides mathematical functions, e.g., `math.sqrt(4)` returns `2`, `math.pi` returns `3.141592653589793`, `math.sin(math.pi/2)` returns `1.0`

## Python Operators

- `+`: addition, string concatenation, list concatenation
- `-`: subtraction, negation, list difference
- `*`: multiplication, repetition, list repetition
- `/`: division
- `//`: floor division
- `%`: modulus, string formatting
- `**`: exponentiation
- `<`: less than
- `<=`: less than or equal to
- `>`: greater than
- `>=`: greater than or equal to
- `==`: equal to
- `!=`: not equal to
- `and`: logical and
- `or`: logical or
- `not`: logical not
- `+=`: addition assignment
- `-=`: subtraction assignment

## Python Control Structures

- `if`: conditional statement that executes a block of code if a condition is true
- `elif`: conditional statement that executes a block of code if the previous if-condition is false and the current condition is true
- `else`: conditional statement that executes a block of code if the previous if-condition is false

- `for`: loop that iterates over a sequence of elements, e.g., `for i in range(5): print(i)` prints `0, 1, 2, 3, 4`
- `while`: loop that executes a block of code as long as a condition is true, e.g., `while i < 5: print(i); i += 1` prints `0, 1, 2, 3, 4`
- `break`: statement that exits a loop, e.g., `while True: print("Hello, World!"); break` prints "Hello, World!"

## Python Definitions

- **Function heading ("def")**: first line of a function definition, contains the keyword "def", the function name, the parameter list, and a colon
- **Function body**: block of statements that define the function
- **Procedure**: function that does not return a value
- **Parameter**: variable that receives an argument value
- **Argument**: value that is passed to a function
- **Control structure**: block of code that controls the flow of a program, e.g., if, for, while
- **Controlled code**: the block of code that is controlled by a control structure, e.g., the block of code that is executed if an if statement is true
- **Function call**: statement that executes a function and hands over arguments
- **Functional programming**: programming paradigm that uses functions as the primary building blocks of a program
- **Bulk testing**: testing with a large number of test cases, inputted by the user
- **Edge case**: a test case that is at the boundary of what is expected, e.g., a triangle with all sides of length 0; a triangle with a + b = c (a line)
- **Debugging**: the process of finding and fixing errors in a program

## Python Data Types

- `int`: integer number, e.g., `42`
- `float`: floating point number, e.g., `3.14`
- `str`: string, e.g., "Hello, World!"
- `list`: ordered collection of elements that can be changed via indexing, e.g., `[1, 2, 3]`
- `tuple`: ordered collection of elements that cannot be changed after creation, e.g., `(1, 2, 3)`
- `bool`: boolean value acquired by a logical operation, e.g., `1 == 1` returns `True`
- `None`: special constant that represents the absence of a value or a null value. It is an object of its own datatype, the NoneType