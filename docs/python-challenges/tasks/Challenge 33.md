# Black chessboard square

## Your task

Write a Python program for this task.

Check whether a chessboard square is black. Rows and columns are numbered 1–8. Square (1, 1) is black. Colours alternate along every row and column.

## What to enter

Two whole numbers from 1 to 8: column, then row. Type each number on a new line, pressing Enter after each one.

## What your program should show

Show `YES` for black; `NO` for white.

Only show the result described above. Do not add extra words such as "Enter a number" or "The answer is" unless this task asks for them.

Use capital letters for these messages.

## Hint

??? tip "Show a hint"

    Draw a small part of the board, starting with a black square at (1, 1). Notice how the colour changes when you move one square across or one square up. Look for a repeating pattern in the coordinates.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 33: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 33: test runs</caption>
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
        <td><code>1</code><br><code>1</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code><br><code>2</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>1</code><br><code>3</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">4</th>
        <td><code>1</code><br><code>4</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">5</th>
        <td><code>2</code><br><code>3</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">6</th>
        <td><code>2</code><br><code>4</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">7</th>
        <td><code>3</code><br><code>6</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">8</th>
        <td><code>3</code><br><code>7</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">9</th>
        <td><code>4</code><br><code>3</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">10</th>
        <td><code>4</code><br><code>4</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">11</th>
        <td><code>5</code><br><code>2</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">12</th>
        <td><code>5</code><br><code>3</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">13</th>
        <td><code>6</code><br><code>5</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">14</th>
        <td><code>6</code><br><code>6</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">15</th>
        <td><code>7</code><br><code>1</code></td>
        <td><code>YES</code></td>
      </tr>
      <tr>
        <th scope="row">16</th>
        <td><code>7</code><br><code>2</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">17</th>
        <td><code>8</code><br><code>3</code></td>
        <td><code>NO</code></td>
      </tr>
      <tr>
        <th scope="row">18</th>
        <td><code>8</code><br><code>4</code></td>
        <td><code>YES</code></td>
      </tr>
    </tbody>
  </table>
</div>
