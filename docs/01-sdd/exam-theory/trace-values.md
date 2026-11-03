# Trace values

**Your focus:** Track assignments and work out the exact output.

Each assignment changes the value stored in a variable. Use the **current** value on the right-hand side before storing the result on the left.

```text linenums="1"
SET coins TO 4
SET coins TO coins + 3
SET coins TO coins * 2
SEND coins TO DISPLAY
```

| After line | `coins` | Output |
| --- | --- | --- |
| 1 | 4 | — |
| 2 | 7 | — |
| 3 | 14 | — |
| 4 | 14 | 14 |

!!! warning "Assignment is not an equation to solve"
    `SET coins TO coins + 3` means **read the old value, add 3, store the new value**.

    `SET coins TO 3` replaces the old value with 3. These instructions do different jobs.

## Your turn: order matters

```text linenums="1"
SET first TO 6
SET second TO 2
SET first TO first + second
SET second TO first - second
SEND second TO DISPLAY
```

What is displayed? Write down both variables after each assignment.

??? success "Check your answer"
    **6** is displayed.

    | After line | `first` | `second` |
    | --- | --- | --- |
    | 1 | 6 | Not yet assigned |
    | 2 | 6 | 2 |
    | 3 | 8 | 2 |
    | 4 | 8 | 6 |

    Line 4 uses the updated value of `first`: `8 - 2 = 6`.

---

[Back to Answering Code Questions](../sdd-pupil-guide.md) · [Next: Check conditions](check-conditions.md)
