# Digits in ascending order

## Your task

Write a Python program for this task.

Check whether a positive three-digit number's digits get bigger from left to right. Each digit must be bigger than the one before it.

## What to enter

One whole number from 100 to 999 (including both ends) with three different digits. Type each number on a new line, pressing Enter after each one.

## What your program should show

Show `YES` for digits that get bigger from left to right; otherwise `NO`.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

Use capital letters for these messages.

## Hint

??? tip "Show a hint"

    Read the digits from left to right and compare neighbouring digits. Every step must go upwards. Looking only at the first and last digits could miss something in the middle.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 26: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 26: test runs</caption>
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
        <td><code>179</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>197</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>348</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>963</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>725</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>301</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>149</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>356</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>279</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>406</code></td>
        <td><code>NO</code></td>
      </tr>
    </tbody>
  </table>
</div>
