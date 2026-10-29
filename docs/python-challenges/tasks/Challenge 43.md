# Missing corner of a rectangle

## Your task

Write a Python program for this task.

Find the fourth corner of a rectangle from its other three corners. The rectangle sits straight, with two horizontal sides and two vertical sides. Each corner has an x position (across) and a y position (up or down).

## What to enter

Six whole numbers: x then y for the first corner, then x and y for the second and third corners. The three corners are different and may be given in any order. The rectangle is not flat. Positions can be negative or zero. Type each number on a new line, pressing Enter after each one.

## What your program should show

Missing corner's x coordinate on the first line and y coordinate on the second line.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

## Hint

??? tip "Show a hint"

    Sketch a rectangle and label the coordinates of its corners. A vertical side joins corners with the same x position; a horizontal side joins corners with the same y position. Look at the x positions separately from the y positions.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 43: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 43: test runs</caption>
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
        <td><code>1</code><br><code>5</code><br><code>7</code><br><code>5</code><br><code>1</code><br><code>10</code></td>
        <td><code>7</code><br><code>10</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code><br><code>5</code><br><code>7</code><br><code>10</code><br><code>1</code><br><code>10</code></td>
        <td><code>7</code><br><code>5</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>7</code><br><code>5</code><br><code>1</code><br><code>10</code><br><code>7</code><br><code>10</code></td>
        <td><code>1</code><br><code>5</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1</code><br><code>10</code><br><code>7</code><br><code>5</code><br><code>7</code><br><code>10</code></td>
        <td><code>1</code><br><code>5</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>50</code><br><code>100</code><br><code>50</code><br><code>200</code><br><code>20</code><br><code>200</code></td>
        <td><code>20</code><br><code>100</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>20</code><br><code>100</code><br><code>20</code><br><code>200</code><br><code>50</code><br><code>200</code></td>
        <td><code>50</code><br><code>100</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>50</code><br><code>100</code><br><code>20</code><br><code>100</code><br><code>50</code><br><code>200</code></td>
        <td><code>20</code><br><code>200</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>50</code><br><code>100</code><br><code>20</code><br><code>200</code><br><code>20</code><br><code>100</code></td>
        <td><code>50</code><br><code>200</code></td>
      </tr>
    </tbody>
  </table>
</div>
