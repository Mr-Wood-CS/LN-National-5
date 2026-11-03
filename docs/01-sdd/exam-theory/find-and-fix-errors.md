# Find and fix errors

**Your focus:** Identify a mistake, explain it and correct it.

This algorithm should add three scores, but it contains a mistake.

```text linenums="1"
REPEAT 3 TIMES
    SET total TO 0
    RECEIVE score FROM KEYBOARD
    SET total TO total + score
END REPEAT
SEND total TO DISPLAY
```

For inputs **4, 7, 2**:

1. What does it actually display?
2. Why does that happen?
3. How would you correct it?

??? success "Check your answer"
    1. It displays **2**.
    2. Line 2 resets `total` to zero on every pass, so each previous score is lost. After the last pass, only the last score remains.
    3. Move `SET total TO 0` before `REPEAT 3 TIMES` so the total is initialised once.

---

[Back to Answering Code Questions](../sdd-pupil-guide.md)
