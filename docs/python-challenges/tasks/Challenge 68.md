# Cricket over

## Your task

Use a loop to read the scores for six cricket balls. Add the scores to find the total for the over.

## What to enter

Six whole-number scores, each zero or greater, in ball order. Type each value on a separate line, pressing Enter after each one.

## What your program should show

One line: `This over's score was: t`, replacing t with the total.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    Keep a running total. It should start before any ball is entered and should not be reset for each ball.

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

<div class="challenge-table-scroll" role="region" aria-label="Challenge 68: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 68: test runs</caption>
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
        <td><code>0</code><br><code>2</code><br><code>0</code><br><code>0</code><br><code>4</code><br><code>6</code></td>
        <td><code>This over&#x27;s score was: 12</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>0</code><br><code>0</code><br><code>0</code><br><code>0</code><br><code>0</code><br><code>0</code></td>
        <td><code>This over&#x27;s score was: 0</code></td>
      </tr>
    </tbody>
  </table>
</div>
