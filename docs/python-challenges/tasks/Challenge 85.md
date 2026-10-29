# Cricket over: store the scores

## Your task

Use a loop to read six cricket scores into a list. Then use the stored scores to calculate the over total and display each ball's score in order.

## What to enter

Six whole-number scores, each zero or greater, in ball order. Type each value on a separate line, pressing Enter after each one.

## What your program should show

Show `This over's score was: t`, then `With each ball scoring:`, then the six stored scores on separate lines.

Only show the results and messages described above. Do not add input prompts; the tables below show the information to type.

## Python tools you may need

Try the small examples first if a tool is new to you. These tools are not a finished solution.

- **`input()` — read what someone types.** It gives you text, even when the person types digits.
- **`int()` — turn text into a whole number.** For example, `int("12")` gives the number `12`, which you can use in calculations.
- **`print()` — show a result.** Each separate `print()` starts a new output line. To show two values on one line with a space between them, put a comma between them inside `print()`.
- **Lists — store several related values together.** For example, `colours = ["red", "blue"]` stores two text values in order. In these tasks, a Python list is used as an array.
- **`.append()` — add one value to a list.** `colours.append("green")` adds a new item at the end. Start with `[]` if the list is empty.
- **`for` — repeat a block of instructions.** Indent the instructions that repeat. A for loop can visit each stored list item, or work with a range of numbers.
- **`range()` — choose a fixed number of repeats.** `range(4)` provides four positions: 0, 1, 2 and 3. The stop value is not included.
- **A running total — add each new amount to what is already stored.** Start it at zero before the loop. `total = total + amount` updates it without losing the earlier amounts.
- **f-strings — put a value inside a message.** Put `f` before the opening quotation mark and a variable inside curly brackets. For example, `f"Score: {score}"` inserts the value stored in `score`.

## Hint

??? tip "Show a hint"

    This version needs the scores again after they have been entered. A running total alone cannot remember each ball's score.

## Need a hand?

If you get stuck, use a help page, then return to your program. Ask your teacher if you still need support.

- [Read the lesson on storing values in lists](https://snakify.org/lessons/lists/)
- [Work through the lesson one small step at a time](https://snakify.org/lessons/lists/steps/1/)


## Try your program

1. Run your program.
2. Type the values in the middle column, one per line. If it says no input is needed, just run the program.
3. Compare your result with **You should see**. Keep the same line breaks.
4. Tick the test in your workbook if it matches. If it does not, check your code and try again.
5. Start the program again for the next test.

<div class="challenge-table-scroll" role="region" aria-label="Challenge 85: test runs" tabindex="0">
  <table class="challenge-table challenge-table--tests">
    <caption>Challenge 85: test runs</caption>
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
        <td><code>This over&#x27;s score was: 12</code><br><code>With each ball scoring:</code><br><code>0</code><br><code>2</code><br><code>0</code><br><code>0</code><br><code>4</code><br><code>6</code></td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code></td>
        <td><code>This over&#x27;s score was: 6</code><br><code>With each ball scoring:</code><br><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code><br><code>1</code></td>
      </tr>
    </tbody>
  </table>
</div>
