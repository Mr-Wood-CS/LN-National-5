# Types of Programming Errors

!!! info "What you need to know"

    You should be able to describe and identify syntax, execution and logic errors.

| Type | What happens |
| --- | --- |
| **Syntax** | Python detects that the code breaks a language rule before it can run the code. |
| **Execution** | An operation fails while the program is running. |
| **Logic** | The program runs but gives the wrong result or behaves differently from what was intended. |

## Syntax errors

A syntax error breaks a rule of the programming language. For example, Python requires a colon at the end of an `if` statement's first line and an indented body below it.

=== "With a syntax error"

    ```python
    age = 17
    if age >= 17
        print("Age requirement met")
    ```

=== "Corrected"

    ```python
    age = 17
    if age >= 17:
        print("Age requirement met")
    ```

### Common syntax errors in Python

| Mistake | Example | Python error message | Fix |
| --- | --- | --- | --- |
| Missing colon | `if age >= 17` | `SyntaxError: expected ':'` | Add a colon after the condition. |
| Missing indentation | A `print()` inside a loop starts at the same indentation as the `for` line. | `IndentationError: expected an indented block after 'for' statement on line 1` | Indent the loop body. |
| Missing closing quote | `print("Hello)` | `SyntaxError: unterminated string literal (detected at line 1)` | Close the string with a matching quote. |
| Missing closing bracket | `print("Hello"` | `SyntaxError: '(' was never closed` | Add the closing parenthesis. |
| Using assignment in an equality test | `if age = 17:` | `SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?` | Use `==` to test whether two values are equal. |

These messages are from Python 3.15. The wording and line numbers can vary with the Python version and where the code appears.

If Python reports a syntax error, check the line it points to and the line before it.

## Execution errors

An execution error occurs when the program tries to perform an operation it cannot complete. If the user enters `100` and `0` in this program, Python raises a `ZeroDivisionError`.

```python
first_number = int(input("Enter the first number: "))
second_number = int(input("Enter the second number: "))
print(first_number / second_number)
```

To handle that input, check whether the second number is zero before dividing. If it is zero, display an error and ask for a different number.

### Common execution errors in Python

| Error message | What causes it | Example |
| --- | --- | --- |
| `ZeroDivisionError` | Dividing by zero | `100 / 0` |
| `ValueError` | Using a value that an operation cannot accept | `int("hello")` |
| `TypeError` | Using an operation with incompatible data types | `"Score: " + 10` |
| `IndexError` | Accessing a list index that does not exist | `[10, 20, 30][3]` (the last index is `2`) |
| `NameError` | Using a name that Python cannot find | `print(socre)` when the variable is named `score` |

When an execution error occurs, read the last line of the error message to see the error type. Then look for the line number in your code and check the values the program was using there.

## Logic errors

A logic error occurs when the program runs but does the wrong thing. This program should accept ratings from 0 to 10 inclusive.

```python
rating = int(input("Enter a rating from 0 to 10: "))
if rating >= 0 and rating <= 100:
    print("Rating accepted")
else:
    print("Invalid rating")
```

Entering `11` displays **Rating accepted**, even though the expected result is **Invalid rating**. To fix the error, change the upper limit from `100` to `10`. Testing with only a normal value such as `5` would miss the error because both versions accept it.

### Common logic errors in Python

| Mistake | Example | Fix |
| --- | --- | --- |
| Using the wrong comparison | `age > 17` excludes users who are exactly 17 when the minimum age is 17. | Use `age >= 17`. |
| Using the wrong logical operator | `rating >= 0 or rating <= 10` accepts `11`. | Use `and` so both limits must be met. |
| Repeating a loop too few times | `range(1, 5)` produces the numbers 1 to 4 when you need 1 to 5. | Use `range(1, 6)`. |
| Overwriting a running total | `total = number` leaves only the last number in `total`. | Use `total = total + number` inside the loop. |
| Displaying the wrong variable | `print("Hello", age)` displays the user's age in the greeting. | Display `name` in the greeting. |

[Back to Test Data and Test Tables](01.md)
