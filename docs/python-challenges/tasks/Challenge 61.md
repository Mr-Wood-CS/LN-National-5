# Integer root of a linear equation

## Your task

Write a Python program for this task.

You are given two numbers, a and b. Find a whole number x that makes `a × x = b` true. The number x can be positive, negative or zero, but it cannot be a fraction or decimal.

## What to enter

Two whole numbers: a first, then b. Either number can be zero. Type each number on a new line, pressing Enter after each one.

## What your program should show

Show x if there is exactly one whole number that works. Show `no solution` if no whole number works. Show `many solutions` if every whole number works. Use lowercase letters for these messages.

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
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.
- **`//` — whole-number division.** It tells you how many complete groups fit when sharing positive amounts. For example, `17 // 5` gives `3`.

## Hint

??? tip "Show a hint"

    Try reading the equation as a sentence: a multiplied by a whole number must give b. Think separately about what that sentence means when a is zero. A calculator showing a decimal does not mean there is a whole-number answer.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 61: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 61: test runs</caption>
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
        <td><code>1</code><br><code>-2</code></td>
        <td><code>-2</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>2</code><br><code>-1</code></td>
        <td><code>no solution</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>0</code><br><code>0</code></td>
        <td><code>many solutions</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>5</code><br><code>0</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>0</code><br><code>7</code></td>
        <td><code>no solution</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>10</code><br><code>11</code></td>
        <td><code>no solution</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>1</code><br><code>30000</code></td>
        <td><code>30000</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>-15000</code><br><code>15000</code></td>
        <td><code>-1</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>-29999</code><br><code>24999</code></td>
        <td><code>no solution</code></td>
      </tr>
    </tbody>
  </table>
</div>
