# Rook move

## Your task

Write a Python program for this task.

Check whether a rook can travel between two different squares in one move. A rook moves any positive number of squares horizontally or vertically. Assume there are no other pieces.

## What to enter

Four whole numbers from 1 to 8: starting column, starting row, destination column, destination row. The squares are different. Type each number on a new line, pressing Enter after each one.

## What your program should show

Show `YES` if the move is allowed; otherwise `NO`.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

Use capital letters for these messages.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.

## Hint

??? tip "Show a hint"

    Sketch a starting square and trace a straight horizontal move, then a straight vertical move. Watch what happens to the column and row numbers in each kind of move.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 52: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 52: test runs</caption>
    <thead>
      <tr>
        <th scope="col">Test</th>
        <th scope="col">Type these values<br>one per line</th>
        <th scope="col">You should see</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
        <td><code>4</code><br><code>4</code><br><code>5</code><br><code>5</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>4</code><br><code>4</code><br><code>5</code><br><code>4</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>4</code><br><code>4</code><br><code>5</code><br><code>3</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>4</code><br><code>4</code><br><code>4</code><br><code>5</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>4</code><br><code>4</code><br><code>3</code><br><code>5</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>4</code><br><code>4</code><br><code>4</code><br><code>3</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>4</code><br><code>4</code><br><code>3</code><br><code>4</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>4</code><br><code>4</code><br><code>3</code><br><code>3</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>1</code><br><code>1</code><br><code>1</code><br><code>8</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>1</code><br><code>1</code><br><code>8</code><br><code>8</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td><code>1</code><br><code>1</code><br><code>8</code><br><code>1</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">12</th>
        <td><code>1</code><br><code>8</code><br><code>8</code><br><code>8</code></td>
        <td><code>YES</code></td>
      </tr>
    </tbody>
  </table>
</div>
