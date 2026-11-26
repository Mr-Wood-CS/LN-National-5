# Documentation

!!! info "What you need to know"

    Explain how internal commentary, meaningful identifiers, indentation and white space help someone read and maintain a program.

**Internal documentation** is information within the source code that helps someone understand how the program works. In Python, a comment introduced by `#` is an example of internal documentation. Names, indentation and white space also make the code easier to follow.

## Internal commentary

A useful comment explains the purpose of a block of code or records a rule that is hard to infer from the instructions alone. For example, a comment can explain that the score limit is 20 because the score is entered as a mark out of 20. A comment such as `# Set total to zero` above `total = 0` adds little because the instruction already says what happens. Update a comment when the rule it describes changes.

## Meaningful identifiers

An **identifier** is a name used in the program, such as the name of a variable. Choose a name that describes what the value represents. For example, `score_limit` identifies a maximum permitted score, and `total_score` identifies the sum. Including units in a name such as `ticket_price_pence` helps when a program uses more than one unit.

## Indentation and white space

Python uses **indentation** to decide which statements belong to a block. An indented statement under an `if` runs only when that branch is selected. A statement aligned with the `if` runs after the selection. Use four spaces for each level in these examples.

Other **white space** includes blank lines between stages of a program and spaces around operators. A blank line can separate input from processing, and the spaces in `total_score + score` make the operands and operator easier to pick out.

## Worked example

```python
score_limit = 20
score = int(input("Enter a whole-number score: "))
total_score = 0

# The assessment is marked out of 20. Only valid marks count towards the total.
if 0 <= score <= score_limit:
    total_score = total_score + score
    print("Score accepted")
else:
    print("Score outside the valid range")
```

The comment explains why the program works with marks out of 20. The names distinguish the entered mark, the limit and the total. The blank line separates initial setup from validation. The indentation shows why an out-of-range score leaves the total at zero.
