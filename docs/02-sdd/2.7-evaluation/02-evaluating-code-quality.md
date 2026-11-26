# Evaluating Code Quality

## Efficient use of coding constructs

Choose constructs that match the work the program needs to do. A fixed loop suits a known number of repetitions. A conditional loop suits repetition that ends when a condition changes. An array lets a program store related values together and use a loop to process them.

The following programs each read three scores and display their total.

=== "Separate input statements"

    ```python
    score_1 = int(input("Enter a score: "))
    score_2 = int(input("Enter a score: "))
    score_3 = int(input("Enter a score: "))
    print(score_1 + score_2 + score_3)
    ```

=== "Fixed loop with a running total"

    ```python
    total_score = 0
    for counter in range(3):
        score = int(input("Enter a score: "))
        total_score = total_score + score

    print(total_score)
    ```

The loop places the repeated input and addition in one block. To read four scores, change the repeat count from 3 to 4. Both versions ask for the same number of inputs and do equivalent work for the user. The improvement is how the repetition is expressed and how easily it can be changed.

A running total is enough when the program only needs the sum. If it must display the individual scores later, store the scores in an array so those values remain available.

## Readability

When evaluating readability, name the feature, point to evidence in the program and explain how that evidence helps someone follow the code.

| Feature | Example evaluation |
| --- | --- |
| Internal commentary | A comment explaining why the valid range ends at 20 records an assessment rule that the comparison alone cannot explain. |
| Meaningful identifiers | `total_score` shows that the variable stores an accumulated score. |
| Indentation | The indentation places the input and addition inside the loop and shows that the final output runs after all scores have been entered. |
| White space | The blank line before `print(total_score)` visually separates the repeated processing from the final output. |

An evaluation can also identify a specific improvement. For example, if a variable is called `x` throughout the calculation, renaming it to `total_score` would make its purpose clear when the reader reaches the final output.
