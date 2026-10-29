# Time between two timestamps

## Your task

Write a Python program for this task.

Find elapsed seconds between two times on the same day. The second time is later than, or the same as, the first. Both times are on the same day. If they are the same, the time between them is zero seconds.

## What to enter

Six whole numbers: first hour, first minute, first second, second hour, second minute, second second. Hours are 0–23; minutes and seconds are 0–59. Type each number on a new line, pressing Enter after each one.

## What your program should show

One whole number: elapsed seconds.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.
- **`-` — subtract one number from another.** For example, `9 - 4` gives `5`. The order of the numbers matters.
- **Brackets — control which calculation happens first.** Python works out the part in brackets first: `(2 + 3) * 4` gives `20`.

## Hint

??? tip "Show a hint"

    It is easier to compare two times when they use the same unit. Think about how you could describe each time using only seconds. If the times are identical, should any time have passed?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 19: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 19: test runs</caption>
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
        <td><code>1</code><br><code>1</code><br><code>1</code><br><code>2</code><br><code>2</code><br><code>2</code></td>
        <td><code>3661</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code><br><code>2</code><br><code>30</code><br><code>1</code><br><code>3</code><br><code>20</code></td>
        <td><code>50</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>6</code><br><code>54</code><br><code>4</code><br><code>14</code><br><code>18</code><br><code>42</code></td>
        <td><code>26678</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1</code><br><code>49</code><br><code>28</code><br><code>14</code><br><code>7</code><br><code>55</code></td>
        <td><code>44307</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>4</code><br><code>16</code><br><code>9</code><br><code>12</code><br><code>6</code><br><code>7</code></td>
        <td><code>28198</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>5</code><br><code>13</code><br><code>38</code><br><code>5</code><br><code>13</code><br><code>38</code></td>
        <td><code>0</code></td>
      </tr>
    </tbody>
  </table>
</div>
