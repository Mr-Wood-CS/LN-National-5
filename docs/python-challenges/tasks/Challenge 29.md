# Day of the week

## Your task

Write a Python program for this task.

Identify the weekday of a numbered day in a non-leap year where 1 January is Thursday. Day 1 is 1 January.

## What to enter

One whole number from 1 to 365 (including both ends): day number in the year. Type each number on a new line, pressing Enter after each one.

## What your program should show

One weekday number: Sunday 0, Monday 1, Tuesday 2, Wednesday 3, Thursday 4, Friday 5, Saturday 6.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.

## Hint

??? tip "Show a hint"

    Write the weekday numbers in a repeating row, starting from Thursday for day 1. Follow what happens when you pass Saturday. Be careful: the day-of-year count starts at 1, while the weekday numbers include 0.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 29: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 29: test runs</caption>
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
        <td><code>1</code></td>
        <td><code>4</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>2</code></td>
        <td><code>5</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>3</code></td>
        <td><code>6</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>4</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>5</code></td>
        <td><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>50</code></td>
        <td><code>4</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>100</code></td>
        <td><code>5</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>200</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>300</code></td>
        <td><code>2</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>365</code></td>
        <td><code>4</code></td>
      </tr>
    </tbody>
  </table>
</div>
