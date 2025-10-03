# Chapter 2: Variables, Expressions, and Statements

These are comprehensive notes for Chapter 2 from "Think Python 2nd Edition," prepared for this repository and learning workflow.

## 📚 Chapter Summary / Main Concepts
- Variables allow you to store and reuse values in your programs.
- Assignment statements create variables and set their value.
- Variable naming rules: start with a letter or underscore, contain letters/numbers/underscores, and avoid reserved keywords (e.g., class, def).
- Expressions combine values, variables, and operators to produce new values.
- Statements (like assignments and print) perform actions.
- Python runs in two modes:
  - Interactive mode: Type code at the prompt to see immediate results.
  - Script mode: Write code in a file and run it all at once.
- Operator precedence (PEMDAS) determines evaluation order in expressions.
- Strings can be joined with + (concatenation) and repeated with * (repetition).
- Comments are ignored by Python and are useful for explaining code.
- Three types of errors:
  - Syntax errors (bad structure)
  - Runtime errors (exceptions during execution)
  - Semantic errors (code runs but gives unintended/wrong result)

## 🔑 Key Vocabulary
- Variable: Name that refers to a value.
- Assignment: Setting a variable to a value.
- State diagram: Visual representation of current variable values.
- Keyword: Reserved word that can't be used as a name (class, if, for, def, etc.).
- Operand: Value operated on by an operator.
- Expression: Combination producing a value.
- Evaluate: Find the value of an expression.
- Statement: Command/action (assignment, print, etc.).
- Interactive/script mode: Two ways to run Python code.
- Concatenate: Join strings end-to-end.
- Comment: Explanatory text ignored by Python, starts with #.
- Syntax error: Invalid code structure.
- Exception: Error while the program is running.
- Semantic error: Code runs, but gives unintended result.

## 💻 Code Examples Explained

### Assignment and Variables
```python
message = "And now for something completely different"
n = 17
pi = 3.1415926535897932
```
Explanation: Creates variables message, n, and pi with string, integer, and float values.

### Valid and Invalid Variable Names
```python
76trombones = "big parade"   # Invalid (starts with number)
more$ = 1000000              # Invalid ($ not allowed)
class = "Advanced"           # Invalid (reserved keyword)
```
Errors occur for these invalid names.

### Expressions, Operators, and Print Statements
```python
print(n)        # Prints value of n
print(42 * pi)  # Multiplies two values and prints
```
Use +, -, *, /, ** in expressions.

### String Operations
```python
first = 'throat'
second = 'warbler'
print(first + second)   # Concatenation -> throatwarbler
print("Spam" * 3)      # Repetition -> SpamSpamSpam
```

### Comments in Code
```python
# This is a comment describing code
percentage = (minute * 100) / 60  # Percentage of the hour elapsed
```
# starts a comment, ignored by Python.

## 📝 Questions/Exercises With Guidance

### Exercise 2.1: Try Errors on Purpose
- Try `42 = n` (invalid; left side must be a variable).
- Try `x y 1` (error; needs operator).
- Add a semicolon at the end of a statement (allowed; no effect).
- Add a period at the end (error).
- Try multiplying x and y with no operator (`xy`; error).

### Exercise 2.2: Python as Calculator
Volume of a sphere formula: V = (4/3)πr³
```python
import math
r = 5
volume = (4/3) * math.pi * r**3
print(volume)  # Output: 523.598...
```

Bookstore wholesale cost calculation:
```python
price = 24.95
discount = 0.4
copies = 60
first_ship = 3
other_ship = 0.75
total = price * (1 - discount) * copies + first_ship + (copies - 1) * other_ship
print(total)  # Output: 945.45
```

Runner time calculation: Calculate total time for a multi-pace run using addition, multiplication, and time conversion.

## 🎓 Mini-Notes for Beginners
- Test and experiment in interactive mode.
- Always use meaningful variable names; helps understand code.
- Recall operator precedence but use parentheses () for clarity.
- Use comments generously for your future self and collaborators.

## 🔗 Work in Google Colab (Chapter 2)
For an interactive version of these Chapter 2 examples, open the Colab notebook:
- Colab notebook: chapter_2.ipynb

Open in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hrsubhut/think-python-notes/blob/chapter-2-variables-expressions-statements/chapter_2.ipynb)

How to open in Google Colab:
- Click the notebook link above to view it in the repository
- Click the "Open in Colab" badge/link above, or
- Alternatively, open https://colab.research.google.com/, choose the GitHub tab, and paste this repository URL to locate chapter_2.ipynb

## 📄 Reference
Think Python 2nd Edition by Allen B. Downey. PDF for reference: https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/54986323/7a3f2af0-9379-488d-9cc3-861e04910d03/thinkpython2.pdf

---

## Chapter 2 Flashcards
Q: What is a variable in Python?
A: A name that refers to a value stored in memory.

Q: How do you assign a value to a variable?
A: Using the assignment operator = (e.g., x = 5).

Q: Can variable names start with a number?
A: No, they must start with a letter or underscore.

Q: What is a keyword and why can't you use it as a variable name?
A: A reserved word that has a special meaning in Python (like class, def).

Q: What is an expression?
A: A combination of values, variables, and operators that produces a new value.

Q: What is a statement?
A: An instruction that Python executes, such as an assignment or print.

Q: What is operator precedence?
A: The rules that determine the order in which operations are evaluated (PEMDAS).

Q: How do you concatenate two strings?
A: Use the + operator (e.g., 'Hello' + 'World').

Q: How do you repeat a string several times?
A: Use the * operator (e.g., 'Spam' * 3).

Q: How do you write a comment in Python?
A: By starting the line with # (e.g., # This is a comment).

Q: What are the three types of errors in Python?
A: Syntax errors, runtime errors (exceptions), and semantic errors.
