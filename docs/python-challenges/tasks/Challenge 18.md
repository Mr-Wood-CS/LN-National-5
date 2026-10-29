# Elapsed hours and minutes

## Your task

Write a Python program for this task.

Report total complete hours and total complete minutes elapsed since midnight. Give two totals: all the full hours since midnight and all the full minutes since midnight. The minutes total can be greater than 59.

## What to enter

One whole number: seconds since midnight, from 0 to 86399 (including both ends). Type each number on a new line, pressing Enter after each one.

## What your program should show

Two whole numbers on one line separated by one space: complete hours (0–23), then complete minutes (0–1439). Count only full hours and full minutes. Ignore any seconds left over.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`//` — whole-number division.** It tells you how many complete groups fit when sharing positive amounts. For example, `17 // 5` gives `3`.

## Hint

??? tip "Show a hint"

    Both answers describe the time since midnight. The minutes answer is a total, so it does not start again when a full hour passes. Think about the number of seconds in each unit of time.

## Need a hand?

If you are stuck, try one of these help pages, then come back to your program.

- [Read the lesson on entering information and showing results](https://snakify.org/lessons/print_input_numbers/)
- [Work through the same lesson one small step at a time](https://snakify.org/lessons/print_input_numbers/steps/1/)

If you are still unsure, ask your teacher to help you understand the task.


## Try your program

Use the tests below to check your program. You do not need to make up your own numbers.

1. Run your program.
2. Type the values in the middle column, one at a time. Press Enter after each line.
3. Compare your result with the last column. It should match.
4. If it matches, tick that test in your workbook. If it does not, check your code and try again.
5. Run your program again for the next test.

Where a table cell has several lines, keep the same line breaks when typing or comparing the result.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 18: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 18: test runs</caption>
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
        <td><code>3900</code></td>
        <td><code>1 65</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>8000</code></td>
        <td><code>2 133</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>100</code></td>
        <td><code>0 1</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>59</code></td>
        <td><code>0 0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>12345</code></td>
        <td><code>3 205</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>86010</code></td>
        <td><code>23 1433</code></td>
      </tr>
    </tbody>
  </table>
</div>
