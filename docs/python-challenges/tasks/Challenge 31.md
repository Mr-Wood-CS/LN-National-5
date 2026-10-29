# Clock-hand angle

## Your task

Write a Python program for this task.

Imagine a clock with hands. Both hands move clockwise, and the hour hand moves gradually between the hour numbers. You are given the hour hand's angle, measured clockwise from 12 o'clock. Work out the minute hand's angle, also measured clockwise from 12 o'clock.

## What to enter

One whole number from 0 to 359: the hour hand's angle in degrees. Zero means the hand points straight at 12. Type each number on a new line, pressing Enter after each one.

## What your program should show

One whole number: minute hand angle from 0 to 359 degrees. At the start of an hour its angle is zero. Do not print a degree symbol.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`%` — remainder, also called modulo.** It tells you what is left after division. For example, `17 % 5` gives `2`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.

## Hint

??? tip "Show a hint"

    Sketch both hands at the start of an hour and part-way through the next hour. The hour hand moves slowly between the hour marks. The minute hand's position depends on how far through the current hour you are, rather than how many whole hours have passed.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 31: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 31: test runs</caption>
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
        <td><code>190</code></td>
        <td><code>120</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>0</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>5</code></td>
        <td><code>60</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>10</code></td>
        <td><code>120</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>15</code></td>
        <td><code>180</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>20</code></td>
        <td><code>240</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>25</code></td>
        <td><code>300</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>29</code></td>
        <td><code>348</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>30</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>31</code></td>
        <td><code>12</code></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td><code>40</code></td>
        <td><code>120</code></td>
      </tr>
      <tr>
        <th scope="row">12</th>
        <td><code>59</code></td>
        <td><code>348</code></td>
      </tr>
      <tr>
        <th scope="row">13</th>
        <td><code>300</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">14</th>
        <td><code>359</code></td>
        <td><code>348</code></td>
      </tr>
      <tr>
        <th scope="row">15</th>
        <td><code>1</code></td>
        <td><code>12</code></td>
      </tr>
    </tbody>
  </table>
</div>
