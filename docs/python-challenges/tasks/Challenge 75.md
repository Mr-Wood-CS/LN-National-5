# Odd number pattern: choose the ends

## Your task

Extend Odd number pattern so the user chooses the first and last odd numbers. Include both entered values in the displayed pattern.

## What to enter

Two odd whole numbers: first and last. The last is greater than or equal to the first. Negative odd numbers are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `Odd Numbers List`, then each number on its own line in increasing order. If both ends are equal, show that number once.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range(start, stop, step)` — count using a chosen gap.** For example, `range(2, 9, 3)` produces 2, 5 and 8. The stop value is not included.
- **`+` — add numbers.** For example, `8 + 4` gives `12`. Make sure the values are numbers: joining text works differently.

## Hint

??? tip "Show a hint"

    Remember that a range stops before its stop value. Think about how to make sure the last requested odd number is included.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on fixed-count loops](https://snakify.org/lessons/for_loop_range/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/for_loop_range/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 75: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 75: test runs</caption>
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
        <td><code>5</code><br><code>13</code></td>
        <td><code>Odd Numbers List</code><br><code>5</code><br><code>7</code><br><code>9</code><br><code>11</code><br><code>13</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>-3</code><br><code>1</code></td>
        <td><code>Odd Numbers List</code><br><code>-3</code><br><code>-1</code><br><code>1</code></td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td><code>7</code><br><code>7</code></td>
        <td><code>Odd Numbers List</code><br><code>7</code></td>
      </tr>
    </tbody>
  </table>
</div>
