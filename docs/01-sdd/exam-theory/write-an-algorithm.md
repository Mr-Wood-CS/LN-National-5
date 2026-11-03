# Write an algorithm

**Your focus:** Build a complete answer from inputs, processes and outputs.

**Practice task:** Input four ticket quantities. Each ticket costs £6. Display the total number of tickets and the total cost.

Before writing code, identify:

| Input | Process | Output |
| --- | --- | --- |
| Four ticket quantities | Add the quantities; multiply the final total by 6 | Total tickets and total cost |

Try writing your own algorithm before opening the solution.

??? success "One possible solution"
    ```text linenums="1"
    SET totalTickets TO 0
    REPEAT 4 TIMES
        RECEIVE quantity FROM KEYBOARD
        SET totalTickets TO totalTickets + quantity
    END REPEAT
    SET totalCost TO totalTickets * 6
    SEND totalTickets TO DISPLAY
    SEND totalCost TO DISPLAY
    ```

    **Quick check:** Inputs `2, 0, 3, 1` give **6 tickets** and a **£36 total cost**.

    The zero quantity still counts as one of the four inputs. It adds nothing to the total.

---

[Back to Answering Code Questions](../sdd-pupil-guide.md) · [Next: Find and fix errors](find-and-fix-errors.md)
