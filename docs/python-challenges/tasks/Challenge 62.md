# Smallest of five numbers

## Your task

Write a Python program for this task.

Report the smallest of five entered whole numbers.

## What to enter

Five whole numbers; negative numbers, zero and repeated numbers are allowed. Type each number on a new line, pressing Enter after each one.

## What your program should show

One whole number: smallest value, displayed once.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Comparison signs — ask a question about numbers.** `<` means less than, `>` means greater than, `<=` means less than or equal to, and `>=` means greater than or equal to.
- **Separate `if` statements — make checks one after another.** Unlike an `if`/`elif` group, several separate `if` statements can all run. A later check sees any values changed by an earlier one.

## Hint

??? tip "Show a hint"

    Keep all five values in mind: the smallest could appear in any position. Could the comparisons you used for two or three numbers help you organise this larger task?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 62: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 62: test runs</caption>
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
        <td><code>10</code><br><code>20</code><br><code>30</code><br><code>40</code><br><code>50</code></td>
        <td><code>10</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>21</code><br><code>11</code><br><code>31</code><br><code>41</code><br><code>51</code></td>
        <td><code>11</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>48</code><br><code>49</code><br><code>47</code><br><code>50</code><br><code>55</code></td>
        <td><code>47</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>10</code><br><code>20</code><br><code>30</code><br><code>40</code><br><code>0</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>100</code><br><code>200</code><br><code>300</code><br><code>20</code><br><code>400</code></td>
        <td><code>20</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>15</code><br><code>16</code><br><code>17</code><br><code>11</code><br><code>12</code></td>
        <td><code>11</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>15</code><br><code>16</code><br><code>17</code><br><code>11</code><br><code>10</code></td>
        <td><code>10</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>16</code><br><code>15</code><br><code>17</code><br><code>21</code><br><code>22</code></td>
        <td><code>15</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>18</code><br><code>19</code><br><code>16</code><br><code>17</code><br><code>30</code></td>
        <td><code>16</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>18</code><br><code>19</code><br><code>5</code><br><code>3</code><br><code>8</code></td>
        <td><code>3</code></td>
      </tr>
    </tbody>
  </table>
</div>
