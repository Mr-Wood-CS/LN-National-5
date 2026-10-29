# Challenge 36: Bishop move

## Your task

Write a Python program for this task.

Check whether a bishop can travel between two different squares in one move. A bishop moves any positive number of squares along a diagonal. Assume there are no other pieces.

## What to enter

Four whole numbers from 1 to 8: starting column, starting row, destination column, destination row. The squares are different. Type each number on a new line, pressing Enter after each one.

## What your program should show

Show `YES` if the move is allowed; otherwise `NO`.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

Use capital letters for these messages.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on making decisions with if, elif and else](https://snakify.org/lessons/if_then_else_conditions/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/if_then_else_conditions/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

| Test | Type these values<br>one per line | You should see |
| --- | --- | --- |
| 1 | <code>4</code><br><code>4</code><br><code>5</code><br><code>5</code> | <code>YES</code> |
| 2 | <code>4</code><br><code>4</code><br><code>5</code><br><code>4</code> | <code>NO</code> |
| 3 | <code>4</code><br><code>4</code><br><code>5</code><br><code>3</code> | <code>YES</code> |
| 4 | <code>4</code><br><code>4</code><br><code>4</code><br><code>5</code> | <code>NO</code> |
| 5 | <code>4</code><br><code>4</code><br><code>3</code><br><code>5</code> | <code>YES</code> |
| 6 | <code>4</code><br><code>4</code><br><code>4</code><br><code>3</code> | <code>NO</code> |
| 7 | <code>4</code><br><code>4</code><br><code>3</code><br><code>4</code> | <code>NO</code> |
| 8 | <code>4</code><br><code>4</code><br><code>3</code><br><code>3</code> | <code>YES</code> |
| 9 | <code>1</code><br><code>1</code><br><code>1</code><br><code>8</code> | <code>NO</code> |
| 10 | <code>1</code><br><code>1</code><br><code>8</code><br><code>8</code> | <code>YES</code> |
| 11 | <code>1</code><br><code>1</code><br><code>8</code><br><code>1</code> | <code>NO</code> |
| 12 | <code>1</code><br><code>8</code><br><code>8</code><br><code>8</code> | <code>NO</code> |
| 13 | <code>1</code><br><code>8</code><br><code>8</code><br><code>1</code> | <code>YES</code> |
| 14 | <code>1</code><br><code>8</code><br><code>1</code><br><code>1</code> | <code>NO</code> |
| 15 | <code>8</code><br><code>8</code><br><code>8</code><br><code>1</code> | <code>NO</code> |
| 16 | <code>8</code><br><code>8</code><br><code>1</code><br><code>1</code> | <code>YES</code> |
| 17 | <code>1</code><br><code>1</code><br><code>1</code><br><code>2</code> | <code>NO</code> |
| 18 | <code>1</code><br><code>1</code><br><code>2</code><br><code>2</code> | <code>YES</code> |
| 19 | <code>4</code><br><code>4</code><br><code>6</code><br><code>6</code> | <code>YES</code> |
| 20 | <code>4</code><br><code>4</code><br><code>6</code><br><code>2</code> | <code>YES</code> |
