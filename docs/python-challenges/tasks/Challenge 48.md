# Count equal numbers

## Your task

Write a Python program for this task.

Read three numbers and work out how many of them are the same.

## What to enter

Three whole numbers; negative numbers and zero are allowed. Type each number on a new line, pressing Enter after each one.

## What your program should show

One whole number: `3` if all are equal, `2` if exactly two are equal, or `0` if all are different.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`if` and `else` — choose between two actions.** The `if` part runs when a condition is true; the `else` part runs otherwise. End each heading with a colon (`:`), and indent the lines underneath it.
- **`elif` — check another possibility.** Use it between `if` and `else` when there are more than two possible outcomes. In one `if`/`elif`/`else` group, only the first matching part runs.
- **`==` and `!=` — compare values.** `==` asks whether two values are the same; `!=` asks whether they are different. Remember that `=` on its own stores a value.
- **`and` — require both checks to be true.** For example, `age >= 12 and age <= 16` checks whether an age is within that range, including the ends.
- **`or` — allow either check to be true.** For example, `choice == "A" or choice == "B"` accepts either of those letters.

## Hint

??? tip "Show a hint"

    Read the three possible outputs before planning your decisions. All three values being the same is a different situation from only two matching. Check that one situation cannot accidentally receive two answers.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 48: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 48: test runs</caption>
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
        <td><code>10</code><br><code>5</code><br><code>10</code></td>
        <td><code>2</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>17</code><br><code>17</code><br><code>-9</code></td>
        <td><code>2</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>4</code><br><code>-82</code><br><code>-82</code></td>
        <td><code>2</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>5</code><br><code>2</code><br><code>4</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>-149</code><br><code>-146</code><br><code>-142</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>666</code><br><code>666</code><br><code>666</code></td>
        <td><code>3</code></td>
      </tr>
    </tbody>
  </table>
</div>
