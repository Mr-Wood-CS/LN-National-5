# Check conditions

**Your focus:** Test boundaries and choose between AND and OR.

A delivery gets free postage when its value is **£25 or more**.

```text
IF orderValue >= 25 THEN
    SEND "Free postage" TO DISPLAY
ELSE
    SEND "Postage charge applies" TO DISPLAY
END IF
```

| Order value | `orderValue >= 25` | Output |
| --- | --- | --- |
| £24 | False | Postage charge applies |
| £25 | True | Free postage |
| £26 | True | Free postage |

Changing `>=` to `>` would charge postage at exactly £25. When checking a condition, try a value **below**, **at**, and **above** the boundary.

## Split compound conditions into parts

For an inclusive valid range of 1 to 20:

=== "Accept a valid value"

    ```text
    number >= 1 AND number <= 20
    ```

    Both comparisons must be true. The number must meet the lower **and** upper limits.

=== "Reject an invalid value"

    ```text
    number < 1 OR number > 20
    ```

    Either comparison being true makes the value invalid. A number can be too small **or** too large.

!!! question "Spot the mistake"
    Could `number < 1 AND number > 20` ever be true for a single number?

??? success "Check your answer"
    No. A number cannot be below 1 and above 20 at the same time. To detect either kind of invalid value, use **OR**.

---

[Back to Answering Code Questions](../sdd-pupil-guide.md) · [Next: Follow loops](follow-loops.md)
