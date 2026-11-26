# Predefined functions

A **predefined function** performs a task that Python already provides. An **argument** is a value passed into the function. The **return value** is the result the function gives back. You can store it in a variable or use it directly in an expression.

## Random whole numbers with `random.randint()`

`random.randint(low, high)` takes two integer arguments. `low` is the smallest possible result and `high` is the largest. It returns one integer from that range, **including both endpoints**. Import the `random` module before calling the function.

```python
import random

number = random.randint(2, 8)
print(number)
```

Which values could `random.randint(4, 7)` return?

??? example "Reveal answer"

    It can return 4, 5, 6 or 7. Each call returns one of those values.

[Challenge 90 — Guess the number: random target](<../../python-challenges/tasks/Challenge 90.md>)

## Rounding numbers with `round()`

`round(number, digits)` takes the number to round and an optional second argument. For a positive `digits` value, it returns the number rounded to that many decimal places. If you leave out `digits`, `round()` returns the nearest integer.

```python
print(round(3.7))       # 4
print(round(3.746, 2))  # 3.75
```

If a value is exactly halfway between two possible results, Python chooses the even result. For example, `round(2.5)` gives `2` and `round(3.5)` gives `4`.

What does `round(7.286, 2)` return?

??? example "Reveal answer"

    It returns `7.29`. The second argument asks for two decimal places, and the third decimal digit is 6.

[Challenge 81 — Average temperature: check each reading](<../../python-challenges/tasks/Challenge 81.md>)

## Finding the length with `len()`

`len(value)` takes one argument, such as a list or a string. It returns an integer count of the elements in the list or the characters in the string. Spaces count as characters.

```python
names = ["Dopey", "Grumpy", "Doc"]
print(len(names))  # 3
```

The count can set the number of repetitions in a loop, as in `range(len(names))`. [Traversing a 1D Array](04-standard-algorithms/4.1-traversing-a-1d-array.md)

What does `len("AB1 2CD")` return?

??? example "Reveal answer"

    It returns `7`. There are six letters and digits plus one space.

[Challenge 94 — Postcode formatter: check the length](<../../python-challenges/tasks/Challenge 94.md>)
