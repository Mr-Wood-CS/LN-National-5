# 24-hour digital clock

## Your task

Write a Python program for this task.

Find the time on a 24-hour clock after a number of minutes since midnight. The clock returns to midnight after each complete day.

## What to enter

One whole number, zero or greater: elapsed minutes. Values may exceed 1439. Type each number on a new line, pressing Enter after each one.

## What your program should show

Two whole numbers on one line separated by one space: hour (0–23), then minute within that hour (0–59). Do not put a zero before a one-digit number, and do not use a colon (:).

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Hint

??? tip "Show a hint"

    Separate the idea of complete hours from the minutes left within the current hour. Unlike the earlier elapsed-minutes challenge, the minutes shown on this clock never reach 60. What happens after a complete day?

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
        <td><code>150</code></td>
        <td><code>2 30</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>180</code></td>
        <td><code>3 0</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>444</code></td>
        <td><code>7 24</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1111</code></td>
        <td><code>18 31</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>1439</code></td>
        <td><code>23 59</code></td>
      </tr>
    </tbody>
  </table>
</div>
