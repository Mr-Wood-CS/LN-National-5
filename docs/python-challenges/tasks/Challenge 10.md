# Area of a right-angled triangle

## Your task

Write a Python program for this task.

Calculate the area of a right-angled triangle. The base and perpendicular height are in centimetres. Triangle area is half the base multiplied by the height.

## What to enter

Two positive numbers: base, then perpendicular height. Decimal values are allowed. Type each number on a new line, pressing Enter after each one.

## What your program should show

One number: area in square centimetres. Do not round the result. If the area is a whole number, it is fine to show it with or without .0.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Python tools you may need

These are tools you can use, rather than the steps for solving the task. The small examples use different information from the challenge.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **Variables — keep information for later.** For example, `score = 8` stores a value using the name `score`. A single `=` stores a value; it does not compare two values.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`*` — multiply numbers.** For example, `6 * 4` gives `24`. Python uses `*`, rather than the multiplication sign you may use on paper.
- **`/` — divide, keeping the decimal part.** For example, `7 / 2` gives `3.5`.

## Hint

??? tip "Show a hint"

    Sketch the triangle and label its base and perpendicular height. Think about how it compares with a rectangle of the same base and height. Could the area have a decimal part?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 10: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 10: test runs</caption>
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
        <td><code>3</code><br><code>5</code></td>
        <td><code>7.5</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>10</code><br><code>2</code></td>
        <td><code>10.0</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>179</code><br><code>1534</code></td>
        <td><code>137293.0</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1543</code><br><code>57</code></td>
        <td><code>43975.5</code></td>
      </tr>
    </tbody>
  </table>
</div>
