# Follow loops

**Your focus:** Track each pass and build a running total.

First identify what repeats. Then find what changes and when the condition is checked.

| Loop | What controls it? | What to watch for |
| --- | --- | --- |
| Fixed repetition, such as `REPEAT 5 TIMES` | A set number of passes | Count every pass |
| `WHILE … DO` | A condition checked before the body | The body may run zero times |
| `REPEAT … UNTIL` | A condition checked after the body | The body runs at least once; it stops when the condition is true |

## Worked example: keep asking until the input is valid

```text linenums="1"
REPEAT
    RECEIVE locker FROM KEYBOARD
UNTIL locker >= 1 AND locker <= 20
SEND "Locker accepted" TO DISPLAY
```

Suppose the user enters **0, 23, then 12**.

| Pass | Input | `locker >= 1` | `locker <= 20` | Whole condition | Next step |
| --- | --- | --- | --- | --- | --- |
| 1 | 0 | False | True | False | Ask again |
| 2 | 23 | True | False | False | Ask again |
| 3 | 12 | True | True | True | Leave the loop |

The input instruction runs **three times**. `Locker accepted` appears **once**, after the loop.

!!! warning "Can the value change?"
    If the input is moved before this loop and nothing inside changes `locker`, an invalid value will stay invalid. The loop cannot reach its stopping condition.

## Worked example: build a running total

```text linenums="1"
SET total TO 0
REPEAT 3 TIMES
    RECEIVE score FROM KEYBOARD
    SET total TO total + score
END REPEAT
SEND total TO DISPLAY
```

For inputs **4, 7, 2**:

| Pass | `score` | `total` before addition | `total` after addition |
| --- | --- | --- | --- |
| 1 | 4 | 0 | 4 |
| 2 | 7 | 4 | 11 |
| 3 | 2 | 11 | 13 |

The output is **13**.

- Initialise `total` **before** the loop so it starts at zero once.
- Add to `total` **inside** the loop so every score is included.
- Display `total` **after** the loop to show the final answer once.

---

[Back to Answering Code Questions](../sdd-pupil-guide.md) · [Next: Explain code](explain-code.md)
