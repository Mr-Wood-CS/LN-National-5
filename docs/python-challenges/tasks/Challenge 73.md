# Press-up challenge

## Your task

Use a loop to collect the times taken by three pupils to complete 50 press-ups. Find the mean time for the group.

## What to enter

Three positive times in seconds, one per pupil. Decimal values are allowed. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `The average time was:` then the average followed by ` seconds`. Use exactly two decimal places.

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

    The loop counts pupils, not press-ups. Which number represents how many measurements are being averaged?

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 73: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 73: test runs</caption>
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
        <td><code>75</code><br><code>56</code><br><code>60</code></td>
        <td><code>The average time was:</code><br><code>63.67 seconds</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>50</code><br><code>50</code><br><code>50</code></td>
        <td><code>The average time was:</code><br><code>50.00 seconds</code></td>
      </tr>
    </tbody>
  </table>
</div>
