# First digit after the decimal point

## Your task

Write a Python program for this task.

Identify the first digit immediately after the decimal point in a positive decimal number.

## What to enter

One positive number. It can be a whole number or a decimal. Use a full stop for a decimal point. Type each number on a new line, pressing Enter after each one.

## What your program should show

One digit: the first digit after the decimal point. Do not round the number. If you enter a whole number with no decimal point, show `0`.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Hint

??? tip "Show a hint"

    Point to the first position after the decimal point. Later digits must not change your answer, so rounding would cause a problem. What should happen when there is no decimal part?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 13: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 13: test runs</caption>
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
        <td><code>1.79</code></td>
        <td><code>7</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>10.34</code></td>
        <td><code>3</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>0.001</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>179</code></td>
        <td><code>0</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>19.99</code></td>
        <td><code>9</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>179.12</code></td>
        <td><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>5.29</code></td>
        <td><code>2</code></td>
      </tr>
    </tbody>
  </table>
</div>
