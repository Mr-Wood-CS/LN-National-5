# Tens digit

## Your task

Write a Python program for this task.

Identify the digit in the tens position of a whole number that is zero or greater.

## What to enter

One whole number greater than or equal to 0. Type each number on a new line, pressing Enter after each one.

## What your program should show

One digit: the tens digit. Display `0` for a one-digit number.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`//` — whole-number division.** It tells you how many complete groups fit when sharing positive amounts. For example, `17 // 5` gives `3`.
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.
- **Brackets — control which calculation happens first.** Python works out the part in brackets first: `(2 + 3) * 4` gives `20`.

## Hint

??? tip "Show a hint"

    Use a place-value chart with hundreds, tens and units. Which column matters here? Make sure you pick a single digit, even when the entered number has many digits.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on working with numbers](https://snakify.org/lessons/integer_float_numbers/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/integer_float_numbers/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 23: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 23: test runs</caption>
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
        <td><code>1234</code></td>
        <td><code>3</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>73</code></td>
        <td><code>7</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>10</code></td>
        <td><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>987</code></td>
        <td><code>8</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>1000000</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>1</code></td>
        <td><code>0</code></td>
      </tr>
    </tbody>
  </table>
</div>
