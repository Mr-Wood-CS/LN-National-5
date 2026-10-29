# Average temperature

## Your task

Use a loop to read one temperature for each day of a seven-day week. Calculate the mean: total temperature divided by seven.

## What to enter

Seven temperatures, Monday through Sunday. Negative numbers and decimals are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `This week's average was:` on one line and the average followed by ` degrees centigrade` on the next. Always show exactly two digits after the decimal point.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`float()` — turn text into a number that can have a decimal part.** For example, `float("2.5")` gives the number `2.5`.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **`/` — divide, keeping the decimal part.** For example, `7 / 2` gives `3.5`.
- **`:.2f` formatting — show exactly two decimal places.** For example, `f"{3.5:.2f}"` produces `3.50`. This changes how a value is displayed.

## Hint

??? tip "Show a hint"

    Keep the total and the average as separate ideas. Formatting to two decimal places is done when showing the final result.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 69: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 69: test runs</caption>
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
        <td><code>12</code><br><code>14</code><br><code>7</code><br><code>6</code><br><code>7</code><br><code>11</code><br><code>11</code></td>
        <td><code>This week&#x27;s average was:</code><br><code>9.71 degrees centigrade</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>-2</code><br><code>-2</code><br><code>-2</code><br><code>-2</code><br><code>-2</code><br><code>-2</code><br><code>-2</code></td>
        <td><code>This week&#x27;s average was:</code><br><code>-2.00 degrees centigrade</code></td>
      </tr>
    </tbody>
  </table>
</div>
