# Century of a year

## Your task

Write a Python program for this task.

Determine the century containing a year. The first century contains years 1–100, the second contains 101–200, and so on.

## What to enter

One positive whole number year. There is no year zero in this task. Type each number on a new line, pressing Enter after each one.

## What your program should show

One whole number: century number only. Do not add letters such as "st", "nd" or "th".

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`//` — whole-number division.** It tells you how many complete groups fit when sharing positive amounts. For example, `17 // 5` gives `3`.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **Brackets — control which calculation happens first.** Python works out the part in brackets first: `(2 + 3) * 4` gives `20`.

## Hint

??? tip "Show a hint"

    Look closely at the last year of one century and the first year of the next. A year ending in two zeros belongs to the century that is just finishing. Use this to check any rule you plan.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 27: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 27: test runs</caption>
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
        <td><code>1900</code></td>
        <td><code>19</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1901</code></td>
        <td><code>20</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>1950</code></td>
        <td><code>20</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1999</code></td>
        <td><code>20</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>2000</code></td>
        <td><code>20</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>2001</code></td>
        <td><code>21</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>2017</code></td>
        <td><code>21</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>785</code></td>
        <td><code>8</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>1389</code></td>
        <td><code>14</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>1400</code></td>
        <td><code>14</code></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td><code>1401</code></td>
        <td><code>15</code></td>
      </tr>
    </tbody>
  </table>
</div>
